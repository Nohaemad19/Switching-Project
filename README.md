# Enterprise Network Infrastructure – Cisco Packet Tracer

A Cisco Packet Tracer project focused on designing and configuring a redundant enterprise switching network.

The project demonstrates how different switching and network services can work together to provide connectivity, redundancy, VLAN segmentation, and automatic IP address assignment across the network.

## Project Overview

The network is built using multilayer switches, access switches, and routers. It is designed to provide communication between different VLANs while maintaining network availability through redundancy mechanisms.

The main goal of the project was to configure and test the network from the initial VLAN and switching setup through routing, DHCP, redundancy, and connectivity testing.

## Technologies & Protocols

- VLANs
- Inter-VLAN Routing
- DHCP
- HSRP
- RSTP / STP
- EtherChannel
- Trunking (802.1Q)
- Access Ports
- Multilayer Switching
- Static Routing
- Network Redundancy

## Network Features

### VLAN Segmentation
The network is divided into multiple VLANs to separate different groups of devices and reduce unnecessary broadcast traffic.

### Inter-VLAN Routing
Multilayer switches are used to provide communication between different VLANs.

### DHCP
DHCP is configured to automatically assign IP addresses, subnet masks, and default gateways to end devices.

### HSRP
HSRP is implemented between the multilayer switches to provide a virtual default gateway and maintain gateway availability if one multilayer switch becomes unavailable.

### EtherChannel
Multiple physical links are bundled into logical Port-Channels to increase bandwidth and provide link redundancy.

### RSTP
Rapid Spanning Tree Protocol is used to prevent Layer 2 loops while allowing redundant paths to remain available.

### Trunking
802.1Q trunk links are configured between switches to carry traffic from multiple VLANs across the network.

## Testing & Verification

The configuration was tested using Cisco IOS verification commands and end-device connectivity tests, including:

- DHCP address assignment
- Inter-VLAN connectivity
- Same-VLAN connectivity
- HSRP gateway availability
- EtherChannel status
- VLAN and trunk verification
- STP/RSTP status
- Ping tests between network segments

## Project Files

| File | Description |
|------|-------------|
| `Enterprise-Network.pkt` | Main Cisco Packet Tracer project |
| `README.md` | Project documentation |

## How to Open

1. Download the `.pkt` file.
2. Open it using Cisco Packet Tracer.
3. Open the CLI of the network devices to review the configurations.
4. Use the verification commands to test the different protocols and services.

## Purpose

This project was created as practical work to strengthen my understanding of enterprise switching, routing, redundancy, and network troubleshooting using Cisco Packet Tracer.

---

**Tools:** Cisco Packet Tracer  
**Focus:** Networking • Switching • Routing • Redundancy • DHCP
