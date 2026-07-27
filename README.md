# University Campus Network Design

## Project Overview

This project presents the design and implementation of a university campus network using Cisco Packet Tracer. The network connects two campuses (Main Campus and Smaller Campus) while providing secure communication, dynamic routing, VLAN segmentation, and centralized network services.

The project was developed to simulate a real enterprise network infrastructure for a university environment.

---

## Network Topology

![Network Topology](images/Campus-Topology.png)

---

## Project Objectives

- Design a scalable campus network.
- Segment departments using VLANs.
- Enable communication between VLANs.
- Connect multiple campuses.
- Implement dynamic routing using RIP v2.
- Configure DHCP for automatic IP address assignment.
- Provide Email Server connectivity.
- Simulate a real enterprise network environment.

---

## Network Architecture

### Main Campus

The main campus contains three buildings:

### Building 1
- Administration
- Human Resources
- Business
- Finance

### Building 2
- Engineering
- Art & Design

### Building 3
- Student Laboratory
- IT Department

### Smaller Campus

The smaller campus contains:

- Staff Department
- Student Laboratory

---

## VLAN Design

| VLAN | Department | Network |
|------|------------|----------------|
| 10 | Administration | 192.168.1.0/24 |
| 20 | Human Resources | 192.168.2.0/24 |
| 30 | Business | 192.168.3.0/24 |
| 40 | Finance | 192.168.4.0/24 |
| 50 | Engineering | 192.168.5.0/24 |
| 60 | Art & Design | 192.168.6.0/24 |
| 70 | Student Laboratory | 192.168.7.0/24 |
| 80 | IT Department | 192.168.8.0/24 |
| 90 | Staff | 192.168.9.0/24 |
| 100 | Student Laboratory | 192.168.10.0/24 |

---

## Routing

The network uses **RIP Version 2** as the dynamic routing protocol to exchange routes between routers.

---

## Network Services

- DHCP
- Email Server
- Inter-VLAN Routing
- Dynamic Routing (RIP v2)

---

## Technologies Used

- Cisco Packet Tracer
- Cisco Routers 2911
- Cisco Catalyst Switches
- VLAN
- Trunk Links
- Inter-VLAN Routing
- RIP Version 2
- DHCP
- IPv4 Addressing

---

## Skills Demonstrated

- Enterprise Network Design
- VLAN Configuration
- Router Configuration
- Switch Configuration
- Dynamic Routing
- DHCP Configuration
- Network Segmentation
- Campus Network Implementation
- Cisco Packet Tracer

---

## Repository Contents

```
University-Campus-Network-Design/
│
├── Campus_network_project.pkt
├── README.md
└── images/
    └── network-topology.png
```

---

## Author

**Abdelaziz El farjaoui**

Engineering Student – Intelligent, Communicating and Mobile Systems

Interested in:

- Computer Networks
- Network Security
- Cybersecurity
- Artificial Intelligence
- Cloud Computing