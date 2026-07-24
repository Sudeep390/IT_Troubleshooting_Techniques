# 🌐 DNS Issues Troubleshooting

## Issue

User can connect to the internet but cannot access websites by name.

Example:

Internet works:
ping 8.8.8.8


Website fails:
google.com


---

## Possible Causes

- Incorrect DNS server
- DNS cache corruption
- DNS service failure
- Network configuration issue

---

# Troubleshooting Steps

## 1. Test Internet Connection

Command:
ping 8.8.8.8


If successful:

Internet connection is working.

---

## 2. Test DNS Resolution

Command:
nslookup google.com


Check if DNS returns an IP address.

---

## 3. Clear DNS Cache

Command:
ipconfig /flushdns
---

## 4. Check DNS Settings

Command:
ipconfig /all


Verify DNS server addresses.

---

## 5. Test Alternative DNS

Example:

Google DNS:
8.8.8.8
8.8.4.4


Cloudflare:
1.1.1.1


---

# Resolution

| Problem | Solution |
|---|---|
| DNS cache issue | Flush DNS |
| Wrong DNS server | Update DNS settings |
| DNS outage | Use alternative DNS |

---

# Tools Used

- nslookup
- ipconfig
- PowerShell

---

# Skills Demonstrated

✅ DNS Troubleshooting  
✅ Network Analysis  
✅ TCP/IP Knowledge
