# 🖥 PowerShell System Information

## Overview

PowerShell can quickly collect hardware, operating system, and performance information.

---

# Get Computer Information

Command:

```powershell
Get-ComputerInfo
```

Shows:

Windows version

Manufacturer

System details

# Check Operating System

Command:
```powershell
Get-CimInstance Win32_OperatingSystem
```

Displays:

OS version

Last boot time

Memory information

# Check Computer Model
Command:
```powershell
Get-CimInstance Win32_ComputerSystem
```

Shows:

Manufacturer

Model

RAM

# Check CPU Information
Command:
```powershell
Get-CimInstance Win32_Processor
```

Displays:

Processor name

Speed

Number of cores

# Check Installed Memory
Command:
```powershell
Get-CimInstance Win32_PhysicalMemory
```

Used for:

RAM troubleshooting

Hardware inventory

# Check Disk Information
Command:
```powershell
Get-PhysicalDisk
```

Shows:

Disk health

Media type

Capacity

# Find Running Processes
Command:
```powershell
Get-Process
```

Useful for:

High CPU issues

Application troubleshooting

# Stop a Process
Example:
```powershell
Stop-Process -Name chrome
```

Used when:

Application freezes

Program cannot close normally

# Skills Demonstrated

✅ System Administration

✅ Hardware Inventory

✅ Performance Troubleshooting

✅ Windows Management
