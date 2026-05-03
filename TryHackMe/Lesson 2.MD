# 🌐 Lesson 2 – Network Fundamentals  
**Platform:** TryHackMe  

---

## ✅ Rooms Completed

### 1. What is a Network

**Network:**  
A network is a group of devices connected together to share data and resources.

**Internet:**  
The internet is a collection of interconnected networks.

**Identifying Devices:**
- **IP Address:** Used to identify devices on a network (especially across the internet)  
- **MAC Address:** Used to identify devices on a **local network**

---

## 2. Introduction to LAN

**LAN (Local Area Network):**  
A network that covers a small geographic area (e.g., home, school, office)

---

### 🔷 Types of Network Topologies

#### 1. Star Topology  
Devices are connected to a central device (e.g., switch or hub)

**Advantages:**
- Scalable (easy to add more devices)

**Disadvantages:**
- Expensive (requires more cables and hardware)
- High maintenance
- If the central device fails, the entire network goes down

---

#### 2. Bus Topology  
All devices share a single communication line

**Advantages:**
- Cost-effective
- Easy to set up

**Disadvantages:**
- Prone to bottlenecks
- Difficult to troubleshoot
- Failure of the main cable affects the entire network

---

#### 3. Ring Topology  
Devices are connected in a circular loop

**Advantages:**
- No data collisions (data flows in one direction)

**Disadvantages:**
- Inefficient compared to modern topologies
- A single cable failure can break the entire network

---

### 🔌 Networking Devices

**Switch:**  
A device that connects multiple devices within a LAN using physical cables

**Router:**  
A device that connects different networks together (e.g., your LAN to the internet)

---

### 🌐 Subnetting (Primer)

Subnetting is the process of dividing a network into smaller subnetworks.

An IP address consists of:
- **Network address**
- **Host address**
- **Subnet mask** (defines the division between network and host)

**Default Gateway:**  
The IP address of the router that allows communication with other networks

---

### 🔁 ARP (Address Resolution Protocol)

- Maps an **IP address to a MAC address**
- Used within a local network to locate devices

---

### 📡 DHCP (Dynamic Host Configuration Protocol)

Automatically assigns IP addresses to devices.

**Process (DORA):**
1. Discover  
2. Offer  
3. Request  
4. Acknowledge  

---

## 3. OSI Model (Open Systems Interconnection Model)

A networking framework made up of **7 layers**:

| Layer | Name | Function |
|------|------|----------|
| 7 | Application | Interface for user interaction (e.g., browsers, apps) |
| 6 | Presentation | Translates and formats data (encryption, compression) |
| 5 | Session | Manages connections (start, maintain, end) |
| 4 | Transport | Ensures data delivery using TCP/UDP and ports |
| 3 | Network | Handles routing and IP addressing (e.g., IP, OSPF, RIP) |
| 2 | Data Link | Uses MAC addresses for local delivery |
| 1 | Physical | Transmits raw bits via physical media (cables, signals) |

---

## 📝 Additional Notes

### IP Address
- Consists of **4 octets** (IPv4), each ranging from **0–255**
- Types:
  - **Public IP:** Used on the internet
  - **Private IP:** Used within local networks

---

### Private IP Ranges
- 10.0.0.0 – 10.255.255.255  
- 172.16.0.0 – 172.31.255.255  
- 192.168.0.0 – 192.168.255.255  

---

### Encapsulation
Encapsulation is the process of adding headers (and sometimes trailers) to data as it moves through the layers of a network model.

---

### IP Versions
- **IPv4:** Standard format (e.g., 192.168.1.1)  
- **IPv6:** Larger address space, made up of 8 groups (supports more devices)

---

## 💻 Commands

### ping
- Used to test connectivity between devices  
- Uses **ICMP (Internet Control Message Protocol)**  
- Can also measure response time (latency)

---
