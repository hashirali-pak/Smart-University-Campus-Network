# 🎓 Smart University Campus Network

![Cisco](https://img.shields.io/badge/Cisco-Packet%20Tracer-blue)
![Course](https://img.shields.io/badge/Course-CSE--203L-orange)
![Project](https://img.shields.io/badge/Project-Networking-green)
![Status](https://img.shields.io/badge/Status-Completed-brightgreen)

---

# 📖 Project Overview

This project presents the design and implementation of a **Smart University Campus Network** using **Cisco Packet Tracer**. The network is designed to provide secure, organized and scalable communication between different university departments by implementing **VLAN segmentation, Inter-VLAN Routing, DHCP, DNS and Access Control Lists (ACLs).**

The project demonstrates how a real university campus network can be designed using industry-standard networking concepts and best practices.

This project was developed as part of the **CSE-203L Computer Communication & Networks Lab** course.

---

# 📚 Course Information

| Item | Details |
|------|---------|
| **Course Code** | CSE-203L |
| **Course Title** | Computer Communication & Networks Lab |
| **Project Type** | Semester Lab Project |
| **Software Used** | Cisco Packet Tracer |

---

# 🎯 Project Objectives

- Design a secure and scalable university campus network
- Implement VLAN segmentation for different departments
- Configure Inter-VLAN Routing using Router-on-a-Stick
- Configure DHCP for automatic IP address assignment
- Configure DNS for hostname resolution
- Implement Extended ACLs for network security
- Enable secure communication between departments
- Simulate and verify complete network functionality

---

# 🏛 Network Architecture

The network consists of:

- 🌐 Internet Cloud
- 🌍 Edge Router
- 🛜 Core Router
- 🔀 Distribution Switch
- 🏢 Administration Switch
- 📚 Library Switch
- 👨‍🏫 Faculty Switch
- 💻 Computer Lab Switch
- 🏠 Hostel Switch
- 🖥 Server VLAN
- 💡 Multiple End Devices

---

# 🌐 VLAN Information

| VLAN | Department | Network Address | Default Gateway |
|------|------------|-----------------|-----------------|
| 10 | Administration | 192.168.10.0/24 | 192.168.10.1 |
| 20 | Library | 192.168.20.0/24 | 192.168.20.1 |
| 30 | Faculty | 192.168.30.0/24 | 192.168.30.1 |
| 40 | Computer Lab | 192.168.40.0/24 | 192.168.40.1 |
| 50 | Hostel | 192.168.50.0/24 | 192.168.50.1 |
| 100 | Servers | 192.168.100.0/24 | 192.168.100.1 |

---

# 🔧 Technologies Used

- Cisco Packet Tracer
- Cisco 2911 Router
- Cisco 2960 Switches
- VLAN Segmentation
- IEEE 802.1Q Trunking
- Router-on-a-Stick
- Inter-VLAN Routing
- DHCP
- DNS
- Extended ACLs
- Static Routing
- ICMP Connectivity Testing

---

# 📂 Repository Structure

```
Smart-University-Campus-Network/
│
├── PacketTracer/
│   └── Smart University Campus Network.pkt
│
├── Documentation/
│   └── Project Report.docx
    └── Project Report.pdf
│
├── Configurations/
│   ├── Core-Router.txt
│   ├── Edge-Router.txt
│   ├── Distribution-Switch.txt
│   ├── Administration-Switch.txt
│   ├── Library-Switch.txt
│   ├── Faculty-Switch.txt
│   ├── ComputerLab-Switch.txt
│   └── Hostel-Switch.txt
│
├── Images/
│   ├── Architecture.png
│   ├── Topology.png
│
├── Screenshots/
│   ├── 01-VLAN-Configuration
│   ├── 02-Trunk-Configuration
│   ├── 03-Subinterfaces
│   ├── 04-Routing-Table
│   ├── 05-ACL-Verification
│   ├── 06-DHCP-Server
│   ├── 07-DNS-Server
│
├── README.md
├── LICENSE
```

---

# ✨ Features

- ✅ VLAN Segmentation
- ✅ Router-on-a-Stick
- ✅ Inter-VLAN Routing
- ✅ DHCP Server Configuration
- ✅ DNS Server Configuration
- ✅ Extended ACL Security
- ✅ IEEE 802.1Q Trunking
- ✅ Static Routing
- ✅ Internet Connectivity
- ✅ Packet Tracer Simulation
- ✅ Network Testing & Verification

---

# 🧪 Testing & Verification

The network was successfully tested using Cisco Packet Tracer.

The following functionalities were verified:

- ✔ Successful DHCP IP Assignment
- ✔ DNS Name Resolution
- ✔ Inter-VLAN Communication
- ✔ ACL Restrictions
- ✔ Ping Connectivity Tests
- ✔ Static Route Verification
- ✔ Router-on-a-Stick Operation
- ✔ Packet Flow in Simulation Mode

Project screenshots are available in the **Screenshots** folder.

---

# 📸 Network Topology

The complete network topology and architecture diagrams are available in the **Images** folder.

---

# 🎓 Academic Information

This project was completed as a semester laboratory project for the **CSE-203L Computer Communication & Networks Lab** course.

The implementation follows standard networking concepts, including:

- VLAN Design
- Switching
- Routing
- DHCP
- DNS
- Network Security using ACLs
- Cisco IOS Configuration

---

# 👨‍💻 Author

**Hashir Ali**

**BS Computer Systems Engineering**

---

# 📄 License

This project is licensed under the **MIT License**.

It has been developed for **educational purposes** as part of the **CSE-203L Computer Communication & Networks Lab** course.

---

⭐ *If you found this project useful, consider giving it a star on GitHub!*
