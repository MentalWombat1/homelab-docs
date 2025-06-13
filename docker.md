<style>
 body {
  background-color: #333;
  color: #fff;
  font-family: Arial, sans-serif;
 }
 h1, h2, h3 {
  color: #eee;
 }
 details {
  border: 1px solid #555;
  border-radius: 4px;
  padding: 10px;
  margin-bottom: 10px;
 }
 summary {
  cursor: pointer;
  padding: 5px;
  background-color: #444;
  border-radius: 4px;
 }
 a {
  color: #8ac2ff;
 }
</style>

# Docker Containers

Details on the Docker containers running in the home lab.

## Container 1: Plex Media Server

<details>
 <summary><strong>Plex Configuration</strong></summary>
 <ul>
  <li><strong>Image:</strong> plexinc/pms</li>
  <li><strong>Ports:</strong> 32400:32400, 3005:3005, 8324:8324, 32469:32469/tcp, 32469:32469/udp, 32410:32410/udp, 32412:32412/udp, 32413:32413/udp, 32414:32414/udp</li>
  <li><strong>Volumes:</strong> /path/to/config:/config, /path/to/media:/data</li>
  <li><strong>Purpose:</strong> Media streaming</li>
 </ul>
</details>

## Container 2: Home Assistant

<details>
 <summary><strong>Home Assistant Configuration</strong></summary>
 <ul>
  <li><strong>Image:</strong> homeassistant/home-assistant</li>
  <li><strong>Ports:</strong> 8123:8123</li>
  <li><strong>Volumes:</strong> /path/to/config:/config</li>
  <li><strong>Purpose:</strong> Home automation</li>
 </ul>
</details>

## Container 3: Nextcloud

<details>
 <summary><strong>Nextcloud Configuration</strong></summary>
 <ul>
  <li><strong>Image:</strong> nextcloud</li>
  <li><strong>Ports:</strong> 80:80, 443:443</li>
  <li><strong>Volumes:</strong> /path/to/nextcloud/data:/var/www/html/data, /path/to/nextcloud/config:/var/www/html/config</li>
  <li><strong>Purpose:</strong> Cloud storage</li>
 </ul>
</details>

[Back to Main Page](README.md)
