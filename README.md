# Python Network Security Toolkit
A modular, CLI tool designed for network traffic analysis. Uses python, raw socket handling, multi threaded scanning, and packet sniffing via Scapy. 

## Features
### 1. TCP Port Scanner
- Uses the socket library in Python to attempt TCP handshakes
- Uses multi threading to scan 254 hosts at the same time
- Identifies active hosts on a specific subnet and checks for open ports

### 2. ARP Scanner
- Uses Scapy to create and send out ARP requests across the local network
- Bypasses OS level lists to direclty check the network and returns a mapping of IP addresses to MAC addresses
- Indentifies all devices connected 

### 3. HTTP Packet Sniffer
- Uses Scapy to intercept raw traffic

### Tech Stack
#### Language: 
- Python
#### Libraries:
- scapy
- socket
- threading
- queue

#### Prerequisites 
- OS: Linux (Kali Linux or Ubuntu) or macOS
