#  Network Traffic Analysis Using Wireshark & tcpdump

A hands-on cybersecurity project that demonstrates capturing, monitoring, and analyzing network traffic using **Wireshark** and **tcpdump** on **Kali Linux**. The project focuses on understanding network communication, identifying common protocols, and detecting unusual traffic patterns.

---

#  Project Overview

Network Traffic Analysis (NTA) is the process of capturing and inspecting network packets to understand how devices communicate across a network. It is an essential cybersecurity technique used for troubleshooting, monitoring, and detecting suspicious or malicious activities.

In this project, Wireshark and tcpdump were used to capture live network traffic generated from common network activities such as web browsing and ICMP (ping) requests.

---

#  Objective

* Capture live network traffic.
* Analyze packets and network protocols.
* Understand packet structure and communication.
* Identify unusual or suspicious network activity.
* Gain practical experience with network traffic analysis tools.

---

# Features

* Live packet capture using Wireshark
* Packet capture using tcpdump
* Protocol identification (ICMP, TCP, UDP, DNS, HTTP/HTTPS)
* Packet inspection and filtering
* Save packet captures for offline analysis
* Basic network troubleshooting

---

# Technologies Used

* Kali Linux
* Wireshark
* tcpdump
* Linux Terminal

---

#  Prerequisites

* Kali Linux
* Wireshark
* tcpdump
* Internet connection

Verify the installation:

```bash
wireshark --version
tcpdump --version
```
---

# ⚙️ Installation

Update the system:

```bash
sudo apt update
```

Install Wireshark:

```bash
sudo apt install wireshark
```

Install tcpdump:

```bash
sudo apt install tcpdump
```

Verify installation:

```bash
wireshark --version
tcpdump --version
```

---

# Steps Performed

### 1. Started packet capture using Wireshark.

### 2. Generated network traffic using:

```bash
ping google.com
```

### 3. Captured packets in Wireshark.

### 4. Saved the capture as:

```text
capture_saved.pcapng
```

### 5. Captured packets using tcpdump:

```bash
sudo tcpdump -i eth0 -w traffic.pcap
```

### 6. Stopped the capture using:

```text
Ctrl + C
```

### 7. Analyzed captured packets.

---

# 📊 Results

The project successfully captured and analyzed live network packets using Wireshark and tcpdump.

Observed protocols included:

* ICMP
* TCP
* UDP
* DNS
* HTTP/HTTPS (depending on generated traffic)

Packet information analyzed:

* Source IP Address
* Destination IP Address
* Protocol
* Packet Length
* Packet Details

---

# 📚 Skills Learned

* Packet Sniffing
* Network Traffic Analysis
* Packet Inspection
* Protocol Analysis
* Wireshark Filtering
* tcpdump Usage
* Linux Networking
* Cybersecurity Fundamentals

---



