# Lab 11 – Active Directory PowerShell

## Objective

Used PowerShell to manage and query Active Directory objects, including retrieving user information, checking group membership, creating users, and assigning security groups.

---

## Environment

- Windows Server
- Active Directory Domain Services
- PowerShell
- ActiveDirectory Module

---

## Tasks Completed

- Imported the ActiveDirectory PowerShell module
- Retrieved domain information
- Queried Active Directory users
- Checked user group membership
- Created a new Active Directory user
- Added a user to a security group

---

## Commands Used

```powershell
Import-Module ActiveDirectory

Get-ADDomain

Get-ADUser -Filter *

Get-ADPrincipalGroupMembership mbrown

New-ADUser

Add-ADGroupMember
```

---

## Screenshots

### 1. ActiveDirectory Module and Domain Information

<img width="979" height="512" alt="01-AD module and info" src="https://github.com/user-attachments/assets/026a1fef-5fba-4a77-928d-d809f35dc6b3" />

### 2. User Query

<img width="979" height="512" alt="02-User Query" src="https://github.com/user-attachments/assets/51d86238-f623-42de-9da8-d3776bd97426" />

### 3. Group Membership

<img width="979" height="512" alt="03-Group Membership" src="https://github.com/user-attachments/assets/c6503b4f-8dd5-48cb-b1f8-1b9d29246f7b" />

### 4. User Creation

<img width="979" height="512" alt="04-New user creation" src="https://github.com/user-attachments/assets/cc75b069-85e0-43c0-bfad-0877ff212dfb" />

---

## Key Concepts Learned

- PowerShell automation
- Active Directory management
- User provisioning
- Group management
- Identity lifecycle automation

---

## Real-World Scenario

PowerShell can automate repetitive identity management tasks such as creating accounts, assigning access groups, and onboarding new employees.

---

## Resume Skill

Used PowerShell to automate Active Directory user management tasks, including account creation, group assignment, and identity administration.
