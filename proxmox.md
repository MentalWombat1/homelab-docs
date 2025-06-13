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

# Proxmox Virtual Machine Setup

Details on the Proxmox virtualization environment and VM configurations.

## VM 1: Ubuntu Server

<details>
 <summary><strong>Ubuntu Server Configuration</strong></summary>
 <ul>
  <li><strong>OS:</strong> Ubuntu Server 20.04 LTS</li>
  <li><strong>CPU:</strong> 4 cores</li>
  <li><strong>RAM:</strong> 8GB</li>
  <li><strong>Storage:</strong> 200GB</li>
  <li><strong>Purpose:</strong> Docker host</li>
 </ul>
</details>

## VM 2: Windows Server

<details>
 <summary><strong>Windows Server Configuration</strong></summary>
 <ul>
  <li><strong>OS:</strong> Windows Server 2019</li>
  <li><strong>CPU:</strong> 2 cores</li>
  <li><strong>RAM:</strong> 4GB</li>
  <li><strong>Storage:</strong> 100GB</li>
  <li><strong>Purpose:</strong> Active Directory, DNS</li>
 </ul>
</details>

## Proxmox Configuration

<details>
 <summary><strong>Proxmox Cluster Setup</strong></summary>
 <ul>
  <li><strong>Nodes:</strong> 2</li>
  <li><strong>Networking:</strong> 10.0.0.0/24</li>
  <li><strong>Storage:</strong> Local LVM, NFS share</li>
 </ul>
</details>

[Back to Main Page](README.md)
