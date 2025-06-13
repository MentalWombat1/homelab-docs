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

# pfSense Firewall Configuration

Details on the pfSense firewall setup and configuration.

## General Setup

<details>
 <summary><strong>General Configuration</strong></summary>
 <ul>
  <li><strong>WAN Interface:</strong> DHCP</li>
  <li><strong>LAN Interface:</strong> 10.0.0.1/24</li>
  <li><strong>DNS Servers:</strong> 1.1.1.1, 1.0.0.1</li>
 </ul>
</details>

## Firewall Rules

<details>
 <summary><strong>Firewall Rules Configuration</strong></summary>
 <ul>
  <li><strong>Rule 1:</strong> Allow all outbound traffic</li>
  <li><strong>Rule 2:</strong> Allow SSH on port 22 from specific IP</li>
  <li><strong>Rule 3:</strong> Allow HTTP/HTTPS traffic</li>
 </ul>
</details>

## VPN Setup

<details>
 <summary><strong>VPN Configuration</strong></summary>
 <ul>
  <li><strong>Type:</strong> OpenVPN</li>
  <li><strong>Server Mode:</strong> Remote Access (SSL/TLS)</li>
  <li><strong>Tunnel Network:</strong> 10.0.10.0/24</li>
 </ul>
</details>

[Back to Main Page](README.md)
