# 📡 DHCP Problems Troubleshooting

## Issue

Computer cannot automatically receive an IP address.

---

## Symptoms

- No internet access
- 169.254.x.x IP address
- Network connection limited

---

## Possible Causes

- DHCP server unavailable
- Router issue
- Network adapter problem
- Incorrect network settings

---

# Troubleshooting Steps

## 1. Check IP Address

Command:
ipconfig


Look for:
169.254.x.x


---

## 2. Renew IP Address

Commands:
ipconfig /release

ipconfig /renew


---

## 3. Check Adapter Settings

Open:
ncpa.cpl


Verify:
Obtain IP address automatically


---

## 4. Restart Network Adapter

Disable and enable adapter.

---

# Resolution

| Problem | Solution |
|---|---|
| DHCP failure | Renew IP |
| Wrong settings | Enable automatic IP |
| Router issue | Restart router |

---

# Skills Demonstrated

✅ DHCP Troubleshooting  
✅ IP Address Management  
✅ Network Configuration
