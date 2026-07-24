# Lab 13 – Active Directory User Lifecycle (Joiner, Mover, Leaver)

## Objective

Simulated the Active Directory user lifecycle by managing user accounts through onboarding, role changes, password management, and secure offboarding using PowerShell.

---

## Environment

- Windows Server
- Active Directory Domain Services (AD DS)
- Windows PowerShell
- ActiveDirectory PowerShell Module

---

## Tasks Completed

- Verified an existing Active Directory user account
- Reviewed current security group memberships
- Simulated a department transfer by modifying security groups
- Reset a user's password
- Checked account lockout status
- Disabled a user account as part of the offboarding process

---

## Commands Used

```powershell
Get-ADUser "ava.thomas"

Get-ADPrincipalGroupMembership "ava.thomas"

Remove-ADGroupMember

Add-ADGroupMember

Set-ADAccountPassword

Get-ADUser -Properties LockedOut

Unlock-ADAccount

Disable-ADAccount
```

---

## Screenshots

### 1. Verify Active Directory User

<img width="754" height="515" alt="01-Ava in AD users and comps" src="https://github.com/user-attachments/assets/72119110-dd4a-46b2-94b5-f4bdadf72e28" />


---

### 2. Group Membership Before Department Change

<img width="979" height="512" alt="02-Get AD User" src="https://github.com/user-attachments/assets/e6e2b7fe-dafd-478f-acb9-552c4eb0d503" />

<img width="979" height="512" alt="Ava Groups change" src="https://github.com/user-attachments/assets/659c01ed-9139-41ee-b875-501418c64e24" />

---

### 3. Group Membership After Department Change

<img width="979" height="512" alt="Ava Groups after" src="https://github.com/user-attachments/assets/248e354f-079e-4f47-8e8f-afe5e3ad4191" />

---

### 4. Password Reset Using PowerShell

<img width="979" height="512" alt="04-reset password" src="https://github.com/user-attachments/assets/94f8ed1a-13c9-4331-b9df-40d1ab166b18" />

---

### 5. Account Lockout Status Check

<img width="979" height="512" alt="05-Lockout verify" src="https://github.com/user-attachments/assets/0ec64dbe-fbeb-4402-958a-47490a1c62d6" />

---

### 6. Disabled User Account Verification

<img width="979" height="512" alt="06-Disabled ava" src="https://github.com/user-attachments/assets/b34b4d60-66ed-4c35-ab36-8f0b4d5eabfc" />

---

## Key Concepts Learned

- Joiner, Mover, Leaver (JML)
- User provisioning
- Group-based access control
- Password management
- Account lifecycle management
- Principle of Least Privilege

---

## Real-World Scenario

Simulated an employee's lifecycle within Active Directory. The user account was verified, permissions were updated after a department transfer, the password was reset, account status was checked, and the account was securely disabled instead of deleted after employment ended.

---

## Resume Skill

Managed Active Directory user lifecycle tasks using PowerShell, including user verification, security group management, password resets, account lockout checks, and secure account deprovisioning.
