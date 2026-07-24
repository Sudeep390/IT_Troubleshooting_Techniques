# 🌐 PowerShell Network Commands

## Overview

PowerShell provides commands to diagnose network problems, check connectivity, and collect network information.

---

# View Network Configuration

Command:

```powershell
Get-NetIPConfiguration
```

Purpose:
View IP address
Check gateway
Check DNS settings


---
#View IP Address
Command: 
```powershell
Get-NetIPAddress
```

Shows:
IPv4 address
IPv6 address
Network interface


#Test Network Connectivity
```powershell
Test-NetConnection google.com
```

Checks:
Internet connectivity
DNS resolution
Port availability


#Test Specific Port
Example:
```powershell
Test-NetConnection server01 -Port 443
```
Common ports:
Port	Service
80	HTTP
443	HTTPS
3389	Remote Desktop
22	SSH


#View DNS Information
Command:
```powershell
Resolve-DnsName google.com
```
Purpose:
DNS troubleshooting
Verify name resolution


#View Network Adapter Status
Command:
```powershell
Get-NetAdapter
```
Shows:
Adapter name
Status
Connection speed


#Restart Network Adapter
Command:
```powershell
Restart-NetAdapter -Name "Wi-Fi"
```
Used when:
WiFi stops working
Adapter needs resetting


#Useful Commands
Command	Purpose
Get-NetIPConfiguration	View network settings
Test-NetConnection	Test connectivity
Resolve-DnsName	DNS testing
Get-NetAdapter	Check adapters
Restart-NetAdapter	Restart network

Skills Demonstrated
✅ PowerShell Networking
✅ TCP/IP Troubleshooting
✅ DNS Diagnosis
✅ Network Automation
