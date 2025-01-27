# Cisco Packet Tracer - FTP Server, DHCP Server, and Network Topology Management

This practical project demonstrates the configuration and management of an FTP server, DHCP service, and visualizing network topologies using Cisco Packet Tracer. The project includes steps for setting up an FTP server, configuring DHCP, managing file uploads/downloads, and visualizing network topologies through an interactive dashboard.

## Table of Contents
- [FTP Server Setup](#ftp-server-setup)
- [DHCP Configuration](#dhcp-configuration)
- [Dashboard](#dashboard)
- [Text Editor](#text-editor)
- [File Upload](#file-upload)
- [File Downloading](#file-downloading)
- [Network Topologies](#network-topologies)

## FTP Server Setup
This section covers the steps to configure an FTP server using Cisco Packet Tracer, including IP configuration and starting the FTP services for file transfers.

### Key Points:
- Configure the FTP server's IP address and subnet.
- Enable the FTP service on the server.
- Set up user accounts and permissions for secure file transfers.

## DHCP Configuration
Learn how to configure a DHCP server within Cisco Packet Tracer to dynamically assign IP addresses to network devices. This will automate the IP assignment process for PCs in the network, removing the need for static IP configuration.

### Key Points:
- Set up a DHCP server within Cisco Packet Tracer.
- Define the DHCP address pool (range of IPs available for assignment).
- Configure the network devices (PCs, routers) to receive IP addresses from the DHCP server.
- Configure DHCP options such as the default gateway, DNS server, and lease time.

### Steps:
1. Add a **DHCP Server** device in the simulation.
2. Configure the **DHCP Server** to assign a pool of IP addresses.
3. Connect network devices (PCs, routers) to the network and set their IP configuration to **DHCP**.
4. Ensure that the connected devices automatically receive IP addresses from the DHCP server.

## Dashboard
The dashboard in Cisco Packet Tracer visualizes the network topology, allowing you to interact with devices by clicking on them to view their status and configuration. This interactive interface helps manage the network setup directly within Packet Tracer.

### Features:
- Visualizes network devices and their connections in the simulation.
- Displays device status (online/offline, IP address, etc.).
- Allows device configurations via interactive clicking.

## Text Editor
This feature enables editing of server configuration files directly within Packet Tracer. Modify the server settings or other file configurations without using external tools.

### Usage:
- Access the server within Packet Tracer and open the built-in text editor.
- Modify configuration files as necessary and save them directly.

## File Upload
Learn how to upload files from local devices to the FTP server within Cisco Packet Tracer. This guide includes the steps to establish a connection between the client and FTP server, then upload files accordingly.

### Steps:
- Establish a connection between the client and FTP server.
- Upload files from the client device to the FTP server through the FTP protocol in Packet Tracer.

## File Downloading
Learn how to download files from the FTP server to local devices within Cisco Packet Tracer. This section covers downloading files from the FTP server both within the same network and across different network segments.

### Steps:
- Connect to the FTP server.
- Download files from the server to the local device using the FTP protocol.

## Network Topologies
This project demonstrates two types of network topologies designed in Cisco Packet Tracer:
1. **Star Topology**: A central switch (Switch0) connects multiple PCs, ensuring easy management and scalability.
2. **Bus Topology**: PCs are connected in a linear sequence through switches, forming a simple and cost-effective network.

### Dashboard Images:
- **Left**: Star topology with multiple PCs connected to a central switch (Switch0).
- **Right**: Bus topology where PCs are connected sequentially through switches.

## Installation
1. Clone the repository:  
   `git clone https://github.com/vaishnavipaswan/cisco-packet-tracer-ftp-and-dhcp-server.git`
2. Open the `.pkt` file in Cisco Packet Tracer.
3. Follow the setup and configuration instructions inside the project documentation.

## Usage
- Open the Cisco Packet Tracer simulation and interact with the dashboard to view the network topologies.
- Follow the FTP and DHCP setup guides to upload and download files and configure dynamic IP addressing.
  
## Acknowledgements
- Special thanks to Cisco Packet Tracer for providing the tools to simulate real-world networking scenarios.
- Thanks to the community for continuous support and collaboration.
  
