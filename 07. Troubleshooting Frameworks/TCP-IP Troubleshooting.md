
# 🌐 TCP/IP Troubleshooting

## Overview

TCP/IP is the communication protocol suite used by computers to communicate over networks and the internet.

---

# TCP/IP Model

| Layer | Function | Examples |
|---|---|---|
| Application | User services | HTTP, DNS, FTP |
| Transport | Data delivery | TCP, UDP |
| Internet | Addressing & routing | IP, ICMP |
| Network Access | Hardware communication | Ethernet, WiFi |

---

# Troubleshooting Steps

## 1. Check IP Configuration

Command:
ipconfig


Check:

- IP address
- Subnet mask
- Default gateway
- DNS server

---

## 2. Test Local Connectivity

Ping local gateway:
ping 192.168.1.1

---

## 3. Test Internet Connectivity

Command:
ping 8.8.8.8


---

## 4. Test DNS

Command:
nslookup google.com


---

## 5. Trace Network Path

Command:
tracert google.com


Shows where communication fails.

---

# Common Problems

| Issue | Possible Cause |
|---|---|
| 169.254.x.x IP | DHCP failure |
| Cannot ping gateway | Local network issue |
| Can ping IP but not website | DNS problem |
| Slow connection | Network congestion |

---

# Useful Commands

| Command | Purpose |
|---|---|
| ipconfig | View IP settings |
| ping | Test connectivity |
| tracert | Trace route |
| nslookup | DNS testing |
| netstat | View connections |

---

# Skills Demonstrated

✅ TCP/IP  
✅ DNS Troubleshooting  
✅ Network Diagnostics  
✅ Command Line Tools
