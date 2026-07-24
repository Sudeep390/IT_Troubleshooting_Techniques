# 🔄 Windows Update Troubleshooting

## Issue

User is unable to install Windows updates, updates fail, or the system is stuck during updating.

Common symptoms:

- Update installation failed
- Update stuck at a percentage
- Restart loop after update
- Error codes displayed

---

## 🔍 Possible Causes

- Corrupted Windows Update files
- Low disk space
- Internet connectivity issues
- Disabled update services
- Driver compatibility issues
- Corrupted system files

---

## 🛠 Troubleshooting Steps

### 1. Gather Information

Ask:

- When did the issue start?
- What update failed?
- Is there an error code?
- Was any software or hardware recently installed?

---

### 2. Check Internet Connection

Verify:

- Device has internet access
- VPN is not blocking updates
- Network connection is stable

Test:
ping 8.8.8.8
---

### 3. Check Disk Space

Path:
File Explorer
→ This PC
→ C: Drive

Ensure enough free space is available.

---

### 4. Restart Windows Update Services

Open:
services.msc

Check these services:

- Windows Update
- Background Intelligent Transfer Service (BITS)
- Cryptographic Services

Restart if required.

---

### 5. Run Windows Update Troubleshooter

Path:
Settings
→ System
→ Troubleshoot
→ Other Troubleshooters
→ Windows Update

---

### 6. Reset Windows Update Components

Open Command Prompt as Administrator:

net stop wuauserv

net stop bits

net stop cryptsvc

Clear update cache:
C:\Windows\SoftwareDistribution

Restart services:
net start wuauserv

net start bits

net start cryptsvc
---

### 7. Repair System Files

Run: sfc /scannow

Repair Windows image: DISM /Online /Cleanup-Image /RestoreHealth
---

## ✅ Common Solutions

| Problem | Fix |
|-|-|
| Update stuck | Restart and retry update |
| Corrupted cache | Reset Windows Update components |
| Low storage | Free disk space |
| Service stopped | Restart Windows Update services |
| System corruption | Run SFC/DISM |
| Driver conflict | Update or rollback driver |

---

## 📝 Service Desk Ticket Example

**Issue:**  
User unable to install Windows security update.

**Diagnosis:**  
Windows Update service cache was corrupted.

**Resolution:**  
Reset Windows Update components and ran system file checks.

**Status:**  
Resolved ✅

---

## Skills Demonstrated

✅ Windows Update Management  
✅ Command Prompt Troubleshooting  
✅ Windows Services  
✅ System File Repair  
✅ Incident Documentation
