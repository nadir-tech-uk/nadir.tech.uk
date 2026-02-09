# Networking Foundations: Networking Basics
**Course by Kevin Wallace (LinkedIn Learning)**

This repository contains my study notes and key takeaways from the Networking Foundations course. It covers the fundamental concepts of how data moves across the internet, addressing, hardware, and various networking models.

---

## 📝 Key Learnings

### 1. Internet & Network Connections
* **Wired Connection (Ethernet):**
    * **Connector:** RJ45
    * **Cables:** Cat 5 / Cat 6 (Twisted pair cabling)

### 2. Types of Networks
| Type | Name | Scope & Examples |
| :--- | :--- | :--- |
| **PAN** | Personal Area Network | Very short range (Bluetooth mouse, keyboard, controllers) |
| **LAN** | Local Area Network | Small geographic area (Home, small office) |
| **CAN** | Campus Area Network | Covers a campus or group of buildings |
| **MAN** | Metropolitan Area Network | Covers a city; high-speed connections between offices |
| **WAN** | Wide Area Network | Large regions (countries/continents); e.g., the Internet |
| **VPN** | Virtual Private Network | Secure connection tunnel over a WAN |

### 3. Internet of Things (IoT)
The interconnection of computing devices embedded in everyday objects, enabling them to send and receive data.
* **Examples:** Smart doorbells, refrigerators, Smart TVs, Alexa/Smart assistants.

### 4. Addressing
#### MAC Address (Physical Address)
* **48-bit address** assigned by the manufacturer.
* Known as the "burned-in" address; unique to every device.

#### IP Address (Logical Address)
* **IPv4:** 32-bit address. Structure: `Network | Host`. (Example: `172.16.10.5`)
* **IPv6:** 128-bit address. Structure: `Prefix | Host`. (Example: `23A0:201A:00B2:0000:0000:0400:0001/64`)

### 5. Network Devices
* **Ethernet Switch:** Connects devices within a LAN; uses MAC addresses to forward data.
* **Router:** Connects different networks; uses IP addresses to route traffic.
* **WAP (Wireless Access Point):** Allows wireless devices to connect to a wired network.

### 6. Networking Models
* **OSI Model (Open Systems Interconnection):** A conceptual 7-layer model (Physical, Data Link, Network, Transport, Session, Presentation, Application).
* **TCP/IP Model:** The practical 4-layer model used on the internet today.

### 7. Protocols & Services
* **TCP (Transmission Control Protocol):** Connection-oriented, reliable delivery.
* **UDP (User Datagram Protocol):** Connectionless, fast but "best-effort" delivery.
* **DHCP:** Automatically assigns IP addresses.
* **DNS:** Resolves domain names (e.g., google.com) to IP addresses.
* **NAT:** Translates private IP addresses to a public IP.
* **NTP:** Time synchronization across the network.
* **QoS (Quality of Service):** Prioritizes important traffic like voice or video.

### 8. Wireless Networks
* **Ad Hoc:** No infrastructure; devices connect directly (e.g., AirDrop).
* **Mesh Wireless:** Access points communicate with each other wirelessly to provide flexible coverage.

### 9. Cloud Computing Models
* **SaaS (Software as a Service):** Applications via browser (e.g., Google Workspace).
* **IaaS (Infrastructure as a Service):** Raw computing resources, storage, and networking.
* **PaaS (Platform as a Service):** Provides a platform including OS and hardware abstraction for developers.

---

## ✅ Personal Takeaway
This course provided a strong foundation essential for IT Support, Cloud, and Cybersecurity roles. Understanding how data moves from physical cabling to software applications is the bedrock of IT.
