# Network-Analysis-Wireshark
Practical Wireshark lab: Mastering packet sniffing, advanced display filters, and network protocol analysis.

# Network Analysis & Protocol Mastering with Wireshark

## 📝 Overview
This repository contains my documentation, captures, and analysis from a deep-dive laboratory into network protocols. Using **Wireshark**, I explored the "invisible" layers of communication that power the internet.

* **What is Wireshark?** A world-class network detective tool used to intercept and analyze data traffic in real-time.
* **Objective:** To master packet sniffing, apply advanced filtering, and perform network troubleshooting.

---

## 🚀 Skills Acquired
* **Packet Dissection:** Deep understanding of the **Packet List**, **Details**, and **Bytes** panes.
* **Traffic Filtering:** Proficiency in using Display Filters (e.g., `tcp.flags.reset == 1`) to find needles in haystacks.
* **Protocol Analysis:** Detailed study of the **TCP 3-way handshake**, **DNS** queries, and **DHCP** (DORA).
* **Visualizing Data:** Using I/O Graphs and Protocol Hierarchies to detect network spikes.

---

## 🧪 Hands-on Labs
### 1. TCP Handshake Verification
I captured and analyzed the **SYN -> SYN-ACK -> ACK** sequence to verify reliable connection establishment between a client and a web server.

### 2. Plain-Text Stream Reconstruction
Using the "Follow TCP Stream" feature, I reassembled a session to view the raw HTTP headers, demonstrating how data is exposed when encryption is not used.

### 3. Port Scan Identification
I analyzed the traffic pattern of an **Nmap scan**, identifying how a host responds with **RST** packets when a port is closed.

---

## 🛠️ Tools Used
* **Wireshark:** Primary analysis tool.
* **Nmap:** Used to generate specific traffic for testing.
* **Virtual Machine:** Isolated environment for safe analysis.

---

## 🔒 Privacy & Security
> **Note:** All public IP addresses and sensitive data in these examples have been anonymized or exported as sanitized CSV files to ensure network privacy.
