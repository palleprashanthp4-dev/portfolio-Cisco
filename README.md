<p align="center">
  <img src="images/network-banner.gif" width="100%">
</p>

<h1 align="center">🌐 Prashanth's Cisco Networking Portfolio</h1>

<h3 align="center">
<em>CCNA Aspirant • Network Engineer in Progress • Cisco Packet Tracer Enthusiast</em>
</h3>

<p align="center">

![Cisco](https://img.shields.io/badge/Cisco-Networking-blue)
![CCNA](https://img.shields.io/badge/CCNA-Learning-red)
![Routing](https://img.shields.io/badge/Routing-OSPF-green)
![Switching](https://img.shields.io/badge/Switching-VLAN-orange)
![DHCP](https://img.shields.io/badge/DHCP-Service-blue)
![NAT](https://img.shields.io/badge/NAT-Configuration-yellow)
![GitHub](https://img.shields.io/badge/GitHub-Portfolio-black)

</p>

---

# 👋 About Me

*Passionate Networking Fresher with strong knowledge of Cisco Routing, Switching, Network Fundamentals, and Troubleshooting.*

I enjoy designing and configuring enterprise-style networks using Cisco Packet Tracer and continuously improving my technical skills through hands-on labs and real-world networking scenarios.

### Why Networking?

> *"Networks are the backbone of modern communication. Every packet tells a story, and every route leads to a destination."*

---

# 🎯 Career Objective

Seeking opportunities as:

* Network Engineer
* Network Support Engineer
* NOC Engineer
* IT Support Engineer
* CCNA Fresher

where I can contribute my networking knowledge while learning from industry professionals and building scalable, reliable network infrastructures.

---

# 🛠 Technical Skills

## Routing

* Static Routing
* Default Routing
* OSPF
* Route Verification
* Router Configuration

## Switching

* VLAN Configuration
* Trunk Configuration
* Inter-VLAN Routing
* Port Security
* MAC Address Verification

## Network Services

* DHCP
* DNS
* NAT
* PAT

## Networking Fundamentals

* OSI Model
* TCP/IP Model
* IPv4 Addressing
* Subnetting
* Network Troubleshooting

---

# 🏢 Project 1: Small Office Network

## 📸 Topology
<p align="center">
  <img src="Screenshot 2026-06-08 214426.png" alt="network issue!" width="800">
</p>


### Project Overview

This project simulates a Small Office Network where multiple users are connected through a Cisco switch and communicate within the same LAN.

### Devices Used

| Device            | Count |
| ----------------- | ----- |
| PCs               | 4     |
| Cisco 2960 Switch | 1     |
| Cisco 2911 Router | 1     |

### Skills Demonstrated

✅ IP Addressing

✅ Switch Configuration

✅ Router Configuration

✅ Connectivity Testing

✅ Network Troubleshooting

### Router Configuration

```bash
enable
configure terminal

interface g0/0
ip address 192.168.1.1 255.255.255.0
no shutdown

end
write memory
```

### Verification Commands

```bash
show ip interface brief
show running-config
ping 192.168.1.10
```

### Learning Outcomes

* Understanding LAN communication
* Default Gateway functionality
* Layer 2 switching
* Layer 3 routing basics

---

# 🌍 Project 2: Multi-LAN Enterprise Network

## 📸 Topology
<p align="center">
  <img src="Screenshot 2026-06-08 214237.png" alt="network issue!" width="800">
</p>


### Project Overview

Designed two LANs connected through a Cisco router to enable communication between different networks.

### Features

* Multiple LANs
* Router Connectivity
* End-to-End Communication
* IP Routing

### Router Configuration

```bash
interface g0/0
ip address 192.168.1.1 255.255.255.0
no shutdown

interface g0/1
ip address 192.168.2.1 255.255.255.0
no shutdown
```

### Verification

```bash
show ip route
show ip interface brief
ping 192.168.2.10
```

### Learning Outcomes

* Routing concepts
* Network segmentation
* Gateway management
* Connectivity troubleshooting

---

# 🔥 Project 3: Router-on-a-Stick (Inter-VLAN Routing)

## 📸 Topology
  <img src="Screenshot 2026-06-08 214237.png" alt="network issue!" width="800">
</p>



### Project Overview

Implemented Inter-VLAN Routing using Router-on-a-Stick architecture.

Separate VLANs were created for departments, and a single router interface handled routing between VLANs using subinterfaces.

### VLAN Design

| VLAN    | Department |
| ------- | ---------- |
| VLAN 10 | HR         |
| VLAN 20 | Finance    |
| VLAN 30 | IT         |

### Switch Configuration

```bash
enable
configure terminal

vlan 10
name HR

vlan 20
name FINANCE

vlan 30
name IT

interface fa0/1
switchport mode access
switchport access vlan 10

interface fa0/24
switchport mode trunk
```

### Router Configuration

```bash
interface g0/0
no shutdown

interface g0/0.10
encapsulation dot1Q 10
ip address 192.168.10.1 255.255.255.0

interface g0/0.20
encapsulation dot1Q 20
ip address 192.168.20.1 255.255.255.0

interface g0/0.30
encapsulation dot1Q 30
ip address 192.168.30.1 255.255.255.0
```

### Verification

```bash
show vlan brief
show interfaces trunk
show ip interface brief
ping between VLANs
```

### Learning Outcomes

* VLAN Segmentation
* Trunking
* Inter-VLAN Routing
* Router Subinterfaces
* Enterprise Network Design

---

# 💻 Essential Cisco Commands

| Command                 | Purpose            |
| ----------------------- | ------------------ |
| show ip interface brief | Verify interfaces  |
| show ip route           | View routing table |
| show vlan brief         | View VLANs         |
| show interfaces trunk   | Verify trunks      |
| show running-config     | View configuration |
| ping                    | Test connectivity  |
| traceroute              | Track packet path  |

---

# 📈 Current Learning

* Advanced OSPF
* ACL Configuration
* STP
* EtherChannel
* WAN Technologies
* Network Security
* CCNA Certification

---

# 🏆 Why Hire Me?

✔ Strong Networking Fundamentals

✔ Cisco Packet Tracer Lab Experience

✔ Routing & Switching Knowledge

✔ OSPF Understanding

✔ VLAN Implementation

✔ Troubleshooting Mindset

✔ Quick Learner

✔ Team Player

✔ Passionate About Networking

*I may be a fresher, but I continuously build practical networking skills through hands-on projects, troubleshooting exercises, and self-learning. I am eager to contribute, learn, and grow as a Network Engineer.*

---

# 📫 Connect With Me

### GitHub

https://github.com/palleprashanthp4-dev/portfolio-Cisco

### LinkedIn
https://www.linkedin.com/in/palle-prashanth-p-1616413b8/

### Email

[your-email@example.com](mailto:palleprashanthp4@gmail.com)

---

<h3 align="center">
⭐ Thank You For Visiting My Networking Portfolio ⭐
</h3>

<p align="center">
<em>"Connecting Networks, Building Knowledge, Creating Opportunities."</em>
</p>
