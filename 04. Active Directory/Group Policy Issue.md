# 🏢 Group Policy Issues

## Issue

User settings or company policies are not being applied.

---

## Possible Causes

- Group Policy not updated
- Incorrect Organizational Unit (OU)
- Replication delay
- Policy configuration error

---

## Troubleshooting Steps

### 1. Verify User OU

Ensure the user is located in the correct Organizational Unit.

### 2. Refresh Group Policy

Run:

```
gpupdate /force
```

### 3. Verify Applied Policies

Run:

```
gpresult /r
```

### 4. Restart Computer

Restart and verify policies are applied.

---

## Resolution

| Problem | Solution |
|---------|----------|
| Policy not updated | Run gpupdate /force |
| Wrong OU | Move user to correct OU |
| Policy conflict | Review Group Policy |

---

## Tools Used

- Group Policy Management
- Command Prompt
- ADUC

---

## Useful Commands

Refresh Group Policy:

```
gpupdate /force
```

View Applied Policies:

```
gpresult /r
```

Current Logged-in User:

```
whoami
```

---

## Skills Demonstrated

- Group Policy
- Active Directory
- Windows Administration
