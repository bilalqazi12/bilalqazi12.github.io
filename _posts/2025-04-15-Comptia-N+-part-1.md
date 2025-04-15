---
title:  "CompTIA N+ (Part 1)"
mathjax: true
layout: post
categories: media
---
*Easy Guide to Networking Basics 
*This is the first blog of the CompTIA Network+ Course, which is a beginner-level certification for entering the field of Cybersecurity.*

---

## Networking Fundamentals

**Networking basics:**  
Understanding how computers connect and talk to each other in a network.

**IP & MAC addresses:**  
IP addresses (IPv4/IPv6) are digital addresses for devices. MAC addresses are physical hardware IDs for each device.

**Subnetting:**  
Breaking large networks into smaller sections for better performance and management.

**OSI & TCP/IP models:**  
These are layered models that describe how data travels from one device to another.

---

## OSI Model – Detailed Explanation
  
The OSI (Open Systems Interconnection) model explains how data moves in 7 layers. Each layer has a specific job.

1. **Physical Layer:**  
   Deals with physical connections like cables and signals. Sends raw bits (0s and 1s).  
   *Example: Ethernet cables, fiber optics, hubs*

2. **Data Link Layer:**  
   Sends data between devices on the same network using MAC addresses.  
   *Example: Switches, MAC address, Ethernet*

3. **Network Layer:**  
   Finds the best route for data using IP addresses.  
   *Example: Routers, IPv4, IPv6*

4. **Transport Layer:**  
   Breaks data into smaller pieces and ensures it arrives correctly.  
   *Example: TCP, UDP*

5. **Session Layer:**  
   Starts and manages communication between devices.  
   *Example: Login sessions, video/audio calls*

6. **Presentation Layer:**  
   Formats, compresses, and encrypts data.  
   *Example: JPEG, MP4, SSL/TLS*

7. **Application Layer:**  
   The layer you interact with through apps like browsers or email.  
   *Example: HTTP, FTP, DNS, Gmail, Chrom*

---

## TCP/IP Model 

A simpler, 4-layer model used in real-world internet communication.

1. **Application Layer** – Similar to OSI’s top 3 layers  
2. **Transport Layer** – Same as OSI  
3. **Internet Layer** – Like OSI’s Network Layer  
4. **Network Access Layer** – Combines OSI’s Data Link and Physical layers

---

**Protocols:**  
Standard rules like DNS (website lookup), DHCP (auto IPs), HTTP/S (web browsing), FTP (file transfer), SNMP (monitoring).

**Ports:**  
Special “gates” for communication. Examples:  
- Port 80 = HTTP (web)  
- Port 443 = HTTPS (secure web)  
- Port 21 = FTP (file transfer)  
- Port 22 = SSH (secure terminal)

**Wireless tech:**  
Wi-Fi standards (802.11a/b/g/n/ac/ax), Bluetooth (short range), NFC (tap to pay), RFID (tags/scanning).

**Cables:**  
- **Cat5e, Cat6:** Common Ethernet cables.  
- **Fiber Optic:** Very fast and long-distance.  
- **Plenum vs. PVC:** Fire-safe vs. normal plastic cable jackets.

---

## Network Topologies – (Network Layout Designs)

**Topologies** describe how computers are arranged in a network. Different types suit different needs.

- **Star Topology:**  
  All devices connect to a central switch. Easy to manage, but if the switch fails, everything stops.

- **Bus Topology:**  
  All devices share one main cable. Cheap, but if cable fails, the whole network breaks.

- **Ring Topology:**  
  Devices are connected in a loop. Data passes from one to the next. One failure can affect the whole ring.

- **Mesh Topology:**  
  Every device connects to every other. Very reliable but expensive.

- **Hybrid Topology:**  
  Mix of two or more topologies, used in large networks.

---

## Tech (Virtualization, Cloud, Storage)

**Virtualization:**  
Running multiple virtual computers (VMs) on one physical machine. Saves space and resources.

**Cloud Storage:**  
Store files online (like Google Drive or Dropbox), accessible from anywhere.

**SAN (Storage Area Network):**  
A high-speed storage network used by servers for fast access to data.

**NAS (Network Attached Storage):**  
Like a mini file server — allows file sharing over a local network.

---

## Network Implementations

**Network devices:**  
- **Router:** Sends data between networks  
- **Switch:** Connects devices within a network  
- **Firewall:** Blocks unwanted traffic  
- **Access Point:** Gives Wi-Fi access  
- **Modem:** Connects to internet service provider (ISP)

**Routing:**  
- **Static Routing:** Manually set paths  
- **Dynamic Routing:** Auto path selection using protocols

**Switching:**  
- **VLANs:** Virtual LANs divide traffic  
- **Trunking:** Allows VLANs to travel across switches  
- **Port Mirroring:** For traffic monitoring and analysis

**Wireless setup:**  
SSID = Wi-Fi name  
WPA2/WPA3 = Security  
Channels = Control signal interference

**WAN tech:**  
- **MPLS:** Fast private networks  
- **Metro Ethernet:** High-speed city-wide network  
- **DSL/Cable/Satellite:** Home internet types

**Network services:**  
- **Load Balancer:** Spreads traffic across servers  
- **Proxy Server:** Filters and caches web traffic  
- **VPN Concentrator:** Manages secure remote connections

----

**Stay tuned for Part 2 of CompTIA Network+ **

---
