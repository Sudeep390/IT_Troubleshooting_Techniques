# 🔧 Driver Problems Troubleshooting

## Issue

User reports hardware is not working correctly due to missing, outdated, or corrupted device drivers.

Common symptoms:

- Device not detected
- Hardware not working
- Yellow warning icon in Device Manager
- Poor performance after Windows update

---

## 🔍 Possible Causes

- Missing drivers
- Corrupted driver files
- Outdated drivers
- Incompatible drivers
- Failed Windows update
- Incorrect driver installation

---

## 🛠 Troubleshooting Steps

### 1. Gather Information

Ask:

- Which device is affected?
- When did the issue start?
- Was a Windows update or new hardware installed?
- Is there an error message?

Examples:

- WiFi not working
- Printer not detected
- Sound not working
- Display problems

---

### 2. Check Device Manager

Open:
Device Manager
Look for:

- Yellow ⚠️ warning icons
- Unknown devices
- Disabled devices

Common categories:

- Network adapters
- Display adapters
- Audio devices
- Printers

---

### 3. Check Driver Status

Right-click device:
Properties
→ Driver
Review:

- Driver version
- Driver date
- Error messages

---

### 4. Update Driver

Options:
Device Manager
→ Update Driver
→ Search automatically

or download latest driver from:

- Manufacturer website
- Windows Update

---

### 5. Roll Back Driver

If issue started after update:
Device Manager
→ Device Properties
→ Driver
→ Roll Back Driver

Used when a new driver causes problems.

---

### 6. Reinstall Driver

Steps:
Device Manager
→ Uninstall Device
→ Restart Computer

Windows will automatically reinstall the driver.

---

### 7. Check Windows Updates

Path:
Settings
→ Windows Update
→ Advanced Options
→ Optional Updates

Install available driver updates.

---

## ✅ Common Solutions

| Problem | Fix |
|-|-|
| Missing driver | Install correct driver |
| Corrupted driver | Uninstall and reinstall |
| New driver issue | Roll back driver |
| Hardware not detected | Check connections and drivers |
| WiFi/display issue | Update manufacturer driver |

---

## 📝 Service Desk Ticket Example

**Issue:**  
User unable to connect to WiFi after Windows update.

**Diagnosis:**  
Network adapter driver became corrupted.

**Resolution:**  
Removed old driver and installed latest network driver.

**Status:**  
Resolved ✅

---

## Useful Commands

Check installed drivers: driverquery

View system information: msinfo32

---

## Skills Demonstrated

✅ Device Manager  
✅ Hardware Troubleshooting  
✅ Driver Management  
✅ Windows Administration  
✅ Root Cause Analysis
