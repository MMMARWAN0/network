# Cisco Packet Tracer Project - Multiple LAN Topologies

## 📖 Overview
This project simulates multiple LAN topologies using **Cisco Packet Tracer**.  
The goal is to design and connect different types of LANs (Mesh, Bus, Ring, Star) under a single network using subnetting and a central router.

---

## 🖥️ Network Topologies

### 🔹 LAN A - Mesh Topology
- **Hosts:** 16
- **Network Address:** 192.168.1.0/26  
- **Subnet Mask:** 255.255.255.192  
- **Default Gateway:** 192.168.1.1  
- **Broadcast Address:** 192.168.1.63  
- **Devices:** 4 switches, 3 PCs interconnected in a mesh structure

---

### 🔹 LAN B - Bus Topology
- **Hosts:** 32
- **Network Address:** 192.168.1.64/26  
- **Subnet Mask:** 255.255.255.192  
- **Default Gateway:** 192.168.1.65  
- **Broadcast Address:** 192.168.1.127  
- **Devices:** Multiple switches connected in series (bus), with 3 PCs

---

### 🔹 LAN C - Ring Topology
- **Hosts:** 8
- **Network Address:** 192.168.1.128/26  
- **Subnet Mask:** 255.255.255.192  
- **Default Gateway:** 192.168.1.129  
- **Broadcast Address:** 192.168.1.191  
- **Devices:** 3 switches, 3 PCs connected in a ring structure

---

### 🔹 LAN D - Star Topology
- **Hosts:** 62
- **Network Address:** 192.168.1.192/26  
- **Subnet Mask:** 255.255.255.192  
- **Default Gateway:** 192.168.1.193  
- **Broadcast Address:** 192.168.1.255  
- **Devices:** 1 central switch with 4 PCs connected in a star shape

---

## 🌐 IP Addressing Scheme

| LAN  | Network Address | Subnet Mask       | Default Gateway | Broadcast Address | Hosts Supported |
|------|----------------|-------------------|-----------------|------------------|-----------------|
| A    | 192.168.1.0    | 255.255.255.192   | 192.168.1.1     | 192.168.1.63     | 16              |
| B    | 192.168.1.64   | 255.255.255.192   | 192.168.1.65    | 192.168.1.127    | 32              |
| C    | 192.168.1.128  | 255.255.255.192   | 192.168.1.129   | 192.168.1.191    | 8               |
| D    | 192.168.1.192  | 255.255.255.192   | 192.168.1.193   | 192.168.1.255    | 62              |

---

## ⚙️ Features Implemented
- Subnetting of a **Class C network (192.168.1.0/24)** into 4 subnets  
- Implementation of **Mesh, Bus, Ring, and Star** topologies  
- Interconnection using a **central router**  
- Default gateways configured per LAN  
- End-to-end connectivity with `ping`

---

## 🚀 How to Run
1. Open the project file in **Cisco Packet Tracer**:  
   ```bash
   File > Open > TOPOLOGYS.pkt
