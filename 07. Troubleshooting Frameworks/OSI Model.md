# 🌐 OSI Model

## Overview

The OSI (Open Systems Interconnection) model is a 7-layer framework used to understand and troubleshoot network communication.

---

# OSI Layers

| Layer | Name | Function | Examples |
|---|---|---|---|
| 7 | Application | User applications | HTTP, DNS, FTP |
| 6 | Presentation | Data formatting & encryption | SSL, Encryption |
| 5 | Session | Manages connections | Sessions |
| 4 | Transport | Reliable communication | TCP, UDP |
| 3 | Network | IP addressing & routing | IP, Router |
| 2 | Data Link | MAC addressing | Switch, Ethernet |
| 1 | Physical | Hardware connection | Cable, WiFi |

---

# Troubleshooting Using OSI Model

## Layer 1 - Physical

Check:

- Power connection
- Network cables
- WiFi signal
- Hardware status

Tools:
Cable tester
Device lights


---

## Layer 2 - Data Link

Check:

- Network adapter
- MAC address
- Switch connection

Command:
ipconfig /all


---

## Layer 3 - Network

Check:

- IP address
- Default gateway
- Routing

Commands:
ipconfig
ping
tracert


---

## Layer 4 - Transport

Check:

- Port availability
- Firewall rules

Examples:
TCP 443 - HTTPS
TCP 3389 - RDP
TCP 22 - SSH


---

## Layer 5-7

Check:

- Application settings
- DNS
- Authentication
- Software configuration

---

# Common Example

## Issue:

User cannot access website.

Troubleshooting:

Layer 1:
✅ Check network connection

Layer 3:
✅ Check IP address

Layer 7:
✅ Test browser and DNS

---

# Skills Demonstrated

✅ Networking Fundamentals  
✅ OSI Troubleshooting  
✅ TCP/IP Understanding  
✅ Network Diagnosis
