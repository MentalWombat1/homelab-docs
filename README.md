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

# Home Lab Setup

Welcome to my home lab documentation! This site provides an overview of my home network and server setup.

## Overview

This lab is built to experiment with various technologies, including virtualization, containerization, and network security. Below are the main components:

- Servers: Detailed specifications of the hardware used.
- Proxmox: Configuration and setup of the Proxmox virtualization environment.
- Docker: Information about the Docker containers running on the servers.
- pfSense: Firewall configuration and network setup using pfSense.

## Sections

<details>
 <summary><strong>Hardware</strong></summary>
 <p>Details about the physical servers and their specifications. <a href="hardware.md">View Hardware Specs</a></p>
</details>

<details>
 <summary><strong>Proxmox Setup</strong></summary>
 <p>Information on setting up virtual machines using Proxmox. <a href="proxmox.md">View Proxmox Setup</a></p>
</details>

<details>
 <summary><strong>Docker Containers</strong></summary>
 <p>Details on the Docker containers and their configurations. <a href="docker.md">View Docker Containers</a></p>
</details>

<details>
 <summary><strong>pfSense Firewall</strong></summary>
 <p>Configuration of the pfSense firewall. <a href="pfsense.md">View pfSense Configuration</a></p>
</details>

## Network Diagram

![Network Diagram](network-diagram.png)
*A visual representation of the network architecture.*
