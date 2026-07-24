# Lab 14 – Active Directory Troubleshooting Scenarios

## Objective

Practiced troubleshooting common Active Directory support issues by verifying account status, resetting passwords, checking group memberships, reviewing account lockout status, and investigating account expiration.

---

## Environment

- Windows Server
- Active Directory Domain Services (AD DS)
- Windows PowerShell

---

## Tasks Completed

- Verified Active Directory user accounts
- Confirmed account status
- Reset user passwords
- Verified security group memberships
- Checked account lockout status
- Reviewed account expiration settings

---

## Commands Used

```powershell
Get-ADUser "mike.brown"

Get-ADUser "mike.brown" -Properties Enabled

Set-ADAccountPassword

Get-ADPrincipalGroupMembership "mike.brown"

Get-ADUser "mike.brown" -Properties LockedOut

Unlock-ADAccount

Get-ADUser "mike.brown" -Properties AccountExpirationDate
```

---

## Screenshots

### 1. User Verification and Status

<img width="979" height="512" alt="01-Get user properties and enable cmd" src="https://github.com/user-attachments/assets/6d54d3eb-9958-4432-b8f2-78df1f62c8c6" />

---

### 2. Password Reset

<img width="979" height="512" alt="02-reset password cmd" src="https://github.com/user-attachments/assets/90eff407-8fd6-40ae-ad04-2aab51bf9ba1" />

---

### 3. Group Membership

<img width="979" height="512" alt="03-mike added to group" src="https://github.com/user-attachments/assets/048d63eb-4139-4e0f-bb1f-b03d00ccd3fd" /> <img width="979" height="512" alt="03-group membership status 1" src="https://github.com/user-attachments/assets/b262b7b5-1306-4632-aece-3099c7c4946d" /> <img width="979" height="512" alt="03-group membership status 2" src="https://github.com/user-attachments/assets/509d1552-1a0c-4ec2-8b8a-7ccf570b6c1c" />

---

### 4. Lockout Status

<img width="979" height="512" alt="04-mike lockout" src="https://github.com/user-attachments/assets/e10c02a9-b47f-4a91-85cb-f753fd5622ed" />

---

### 5. Account Expiration

<img width="979" height="512" alt="05-account expiration" src="https://github.com/user-attachments/assets/2ec7f15e-f13f-413c-a8b8-57021b132021" />

---

## Key Concepts Learned

- Account troubleshooting
- Password management
- Group membership verification
- Account lockout investigation
- Account expiration
- Identity troubleshooting

---

## Real-World Scenario

Investigated common Active Directory support requests by verifying user account status, resetting passwords, checking group memberships, reviewing lockout status, and validating account expiration settings before making administrative changes.

---

## Resume Skill

Troubleshot Active Directory user account issues using PowerShell by verifying account status, managing passwords, validating security group memberships, and investigating lockout and account expiration conditions.
