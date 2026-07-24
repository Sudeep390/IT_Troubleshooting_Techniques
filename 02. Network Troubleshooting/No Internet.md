# ❌ No Internet Connection Troubleshooting

## Issue

User cannot access websites, online applications, or network resources.

---

## Symptoms

- "No Internet Access" message
- Websites not loading
- Cannot connect to company resources
- Network icon shows warning

---

## Possible Causes

- Network cable disconnected
- WiFi disabled
- Incorrect IP configuration
- DHCP failure
- DNS issue
- Router/network outage
- Network adapter problem
- Driver issue

---

# Troubleshooting Steps

## 1. Gather Information

Ask:

- Is the issue affecting one user or multiple users?
- Is the device connected through WiFi or Ethernet?
- When did the issue start?
- Were there any recent changes?

---

## 2. Check Physical Connection

Verify:

- Ethernet cable connected
- WiFi enabled
- Airplane mode disabled
- Router/network equipment working

---

## 3. Check IP Configuration

Command:
ipconfig


Check:

- IPv4 Address
- Subnet Mask
- Default Gateway
- DNS Server

---

## 4. Identify DHCP Problems

Normal IP:
192.168.x.x


Problem IP:
169.254.x.x


169.254.x.x means the device failed to get an IP address from DHCP.

---

## 5. Test Network Connectivity

Test local gateway:
ping Default Gateway


Example:
ping 192.168.1.1


Test internet:
ping 8.8.8.8


---

## 6. Test DNS

Command:
nslookup google.com


If IP works but websites fail, DNS may be the issue.

---

## 7. Reset Network Connection

Release IP:
ipconfig /release


Renew IP:
ipconfig /renew


Clear DNS:
ipconfig /flushdns


Reset network:
netsh winsock reset


---

# Resolution

| Problem | Solution |
|---|---|
| DHCP failure | Renew IP address |
| DNS issue | Flush DNS cache |
| Adapter problem | Restart network adapter |
| Driver issue | Update network driver |
| Router issue | Restart network equipment |

---

# Tools Used

- Command Prompt
- PowerShell
- Task Manager
- Device Manager

---

# Skills Demonstrated

✅ TCP/IP Troubleshooting 

✅ Network Diagnostics  

✅ DNS Troubleshooting  

✅ DHCP Troubleshooting  
