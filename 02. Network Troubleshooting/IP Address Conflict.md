# ⚠️ IP Address Conflict Troubleshooting

## Issue

Two devices are using the same IP address causing network problems.

---

## Symptoms

- Intermittent connection
- Network disconnects
- Duplicate IP warning

---

## Possible Causes

- Incorrect static IP assignment
- DHCP configuration issue
- Duplicate device configuration

---

# Troubleshooting Steps

## 1. Check IP Address

Command:
ipconfig


---

## 2. Check MAC Address Mapping

Command:
arp -a


---

## 3. Release and Renew IP

Commands:
ipconfig /release

ipconfig /renew


---

## 4. Check Static IP Settings

Verify no other device uses the same address.

---

# Resolution

| Problem | Solution |
|---|---|
| Duplicate static IP | Assign unique IP |
| DHCP conflict | Restart DHCP service |
| Incorrect configuration | Enable DHCP |

---

# Skills Demonstrated

✅ IP Addressing  
✅ DHCP Troubleshooting  
✅ Network Configuration
