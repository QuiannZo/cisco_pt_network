# Cisco Packet Tracer Project
This project simulates a version of the network used at the Universidad de Costa Rica (UCR). The network is configured using Cisco Packet Tracer and follows the specifications provided in the project guidelines.

<img src="screenshots/Screenshot 2024-12-02 014109.png" alt="N/A" width="950" height="450">

## Features
### Stage 1: ECCI Network
- VLAN segmentation for different labs.
- Layer 3 switches for inter-building connectivity.
- DHCP, NAT, and firewall configurations.
- Wireless access points in each building.
- Internet access via NAT using a pool of public IPs.

### Stage 2: UCR Network and Firewall
- Implementation of four Point of Presence (POP) routers.
- OSPF routing with subnetting using /30 masks.
- Public and private IP addressing for various network segments.
- Firewall configuration to secure web services, restrict ICMP, and allow SSH administration.

## Configuration and Testing

- The project includes configuration dumps for all devices.
- Screenshots demonstrate successful connectivity and security enforcement.
- A detailed subnetting plan justifies the IP allocation.

<img src="screenshots/Screenshot 2024-12-02 014359.png" alt="N/A" width="850" height="600">

<img src="screenshots/Screenshot 2024-12-02 014451.png" alt="N/A" width="850" height="450">

## Tools Used
- Cisco Packet Tracer
- OSPF for dynamic routing
- NAT for private-to-public IP translation
- VLANs and Layer 3 switching for segmentation
- Firewall rules for network security


