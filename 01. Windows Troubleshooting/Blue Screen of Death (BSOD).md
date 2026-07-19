# 💙 Blue Screen of Death (BSOD) Troubleshooting

## Issue

User receives a blue screen error and Windows crashes or restarts unexpectedly.

Common symptoms:

- System crashes suddenly
- Automatic restart
- STOP error code appears
- Unable to access Windows normally

---

## 🔍 Possible Causes

- Faulty device drivers
- Corrupted Windows files
- RAM problems
- Hardware failure
- Failed Windows updates
- Malware
- Overheating

---

## 🛠 Troubleshooting Steps

### 1. Gather Information

Ask:

- When did BSOD start?
- What was the user doing before the crash?
- Is there an error code?
- Did any hardware/software change recently?

Example error:
SYSTEM_SERVICE_EXCEPTION
IRQL_NOT_LESS_OR_EQUAL
MEMORY_MANAGEMENT

---

### 2. Record Stop Code

Check the blue screen message.

Example: STOP CODE: DRIVER_IRQL_NOT_LESS_OR_EQUAL
Use the code to identify the cause.

---

### 3. Check Event Viewer

Open: Event Viewer
→ Windows Logs
→ System

Look for:

- Critical errors
- Kernel-Power events
- Driver failures

---

### 4. Check Drivers

Open: Device Manager
Check for:

- Warning symbols ⚠️
- Recently installed drivers

Actions:

- Update driver
- Roll back driver
- Uninstall faulty driver

---

### 5. Run System Checks

Check Windows files:sfc /scannow
Repair Windows image:

DISM /Online /Cleanup-Image /RestoreHealth
---

### 6. Test Hardware

Check RAM:
Windows Memory Diagnostic

Path:
Start
→ Windows Memory Diagnostic

Check disk: chkdsk
---

## ✅ Common Solutions

| Problem | Fix |
|-|-|
| Driver issue | Update or rollback driver |
| Corrupted files | Run SFC/DISM |
| RAM failure | Replace faulty RAM |
| Disk errors | Run CHKDSK |
| Windows update issue | Remove latest update |
| Overheating | Clean hardware/cooling system |

---

## 📝 Service Desk Ticket Example

**Issue:**  
User experiencing frequent BSOD crashes.

**Diagnosis:**  
Identified outdated graphics driver causing system crashes.

**Resolution:**  
Updated graphics driver and verified system stability.

**Status:**  
Resolved ✅

---

## Skills Demonstrated

✅ Windows Crash Analysis  
✅ Event Viewer  
✅ Driver Troubleshooting  
✅ Hardware Diagnostics  
✅ Command Line Tools  
✅ Root Cause Analysis
