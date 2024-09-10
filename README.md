# HOTEL-NETWORK-CONFIGURATION
USING CISCO-PACKET TRACER





# Grand Horizon Hotel Network Infrastructure

This project outlines the design and configuration of a comprehensive network infrastructure for the **Grand Horizon**, a newly constructed luxury hotel. Using **Cisco Packet Tracer**, the network setup includes serial router configurations, security measures, VLAN segmentation, and DHCP implementation to ensure smooth operations across the hotel.

## Table of Contents

  [Problem Statement](#problem-statement)
  [Objective](#objective)
  [System Description](#system-description)
  [Network Topology](#network-topology)
  [Key Features](#key-features)
  [Requirements](#requirements)
  [Project Structure](#project-structure)
  [Contributing](#contributing)


## Problem Statement

The **Grand Horizon** luxury hotel requires a robust and secure network infrastructure to support multiple stakeholders, including hotel guests, staff, and IoT devices. The hotel management aims to provide seamless internet connectivity, secure communications, and efficient management of the hotel's IT systems across multiple floors and departments.

## Objective

The primary objective of this project is to design a scalable and efficient network tailored to the hotel environment. The design includes:
- VLAN segmentation for traffic management
- Router configurations for inter-VLAN communication
- Security measures including password protection
- DHCP implementation for dynamic IP allocation
- Web server configuration for guest services
- IoT device integration

## System Description

### Admin Office
- Located on the first floor.
- **Router 1** serves as the gateway for administrative traffic and internet access.

### Reception Area
- Connected to the **Admin Office** router.
- Acts as the hub for guest interaction and network services.

### Marketing Department (First Floor)
- Connected via **Router 2** with STICK VLAN segmentation for isolated communication and security.

### IT Department (First Floor)
- Uses **Router 7** with STICK VLAN to manage their resources independently.

### Second and Third Floors
- Use similar VLAN setups, connecting to the central router for internet access.

### Server Room
- Located on the third floor, connected via **Router 3** to ensure access to servers while maintaining security.

## Network Topology

The network setup consists of the following components:

1. **Routers** - Facilitate inter-VLAN communication and provide gateway access to the internet.
2. **Switches** - Connect devices within each VLAN.
3. **PCs** - Represent devices such as laptops and smartphones for both guests and staff.
4. **Web Server** - Hosts services like guest portals and room service requests.
5. **DHCP Server** - Automatically assigns IP addresses to devices across the network.

## Key Features

  **VLAN Segmentation**: Efficient traffic isolation using STICK VLAN configuration for different departments.
  **Security**: Password protection on routers to prevent unauthorized access.
  **Dynamic IP Assignment**: DHCP setup for automatic IP allocation.
  **Web Server**: Provides guest services including room service requests and booking information.
  **Inter-VLAN Communication**: Configured routers to allow seamless communication between different VLANs.

## Requirements

1. Cisco Packet Tracer : Ensure that you have Cisco Packet Tracer installed to run and configure the network simulation.
2. Knowledge of Networking : Basic understanding of routers, switches, VLANs, and DHCP configuration.

3. Open the project in **Cisco Packet Tracer**.

4. Review the configuration of routers and switches for the **VLAN setup**, **DHCP**, and **Web Server**.

5. Customize the network configurations according to your specific needs.

6. Save and test the network connectivity across all devices.

## Project Structure

```
Grand-Horizon-Network/
│
├── configs/
│   ├── router1-config.txt   # Configuration for Router 1 (Admin Office)
│   ├── router2-config.txt   # Configuration for Router 2 (Marketing Department)
│   ├── router3-config.txt   # Configuration for Router 3 (Server Room)
│   └── router7-config.txt   # Configuration for Router 7 (IT Department)
│
├── topology/
│   └── grand-horizon.pkt    # Packet Tracer Network Topology File

```

## Contributing

If you'd like to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a new branch.
3. Make your changes and commit them.
4. Push your changes and submit a pull request.

