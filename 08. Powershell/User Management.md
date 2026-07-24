# 👤 PowerShell User Management

## Overview

PowerShell can automate user management tasks in Windows environments and Active Directory.

---

# View Current User

Command:

```powershell
whoami
```

Shows:

Logged-in username

Domain information

# Get Local Users
Command:
```powershell
Get Local Users
```

Displays:

User accounts

Account status

# Create Local User
Command:
```powershell
New-LocalUser
```
Example:
```powershell
New-LocalUser -Name "TestUser"
```

# Disable User Account
Command:
```powershell
Disable-LocalUser -Name "TestUser"
```

Used when:

Employee leaves company

Account requires restriction

# Enable User Account
Command:
```powershell
Enable-LocalUser -Name "TestUser"
```

# Add User to Group
Example:
```powershell
Add-LocalGroupMember -Group "Administrators" -Member "TestUser"
```

Used for:

Permission management

Local administrator access

# View Local Groups
Command:
```powershell
Get-LocalGroup
```

# Active Directory Commands
Import AD module:
```powershell
Import-Module ActiveDirectory
```

# Find AD User
```powershell
Get-ADUser username
```

# Reset Password
```powershell
Set-ADAccountPassword username
```

# Unlock Account
```powershell
Unlock-ADAccount username
```

# Skills Demonstrated

✅ PowerShell Automation

✅ User Administration

✅ Active Directory Management

✅ Windows Administration
