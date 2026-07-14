# Lab 3 - Active Directory User Administration

## Objective

The goal of this lab was to gain hands-on experience managing user accounts in Active Directory.

This lab simulated common help desk responsibilities by creating user accounts and performing routine administrative tasks.

Skills practiced include:

- Creating users
- Resetting passwords
- Renaming users
- Disabling and enabling accounts
- Deleting users
- Managing password settings

---

# Environment

## Infrastructure

- Cloud Provider: Amazon Web Services (AWS)
- Operating System: Windows Server 2022
- Domain: devonlab.local
- Management Tool: Active Directory Users and Computers (ADUC)

---

# Why User Administration?

Managing user accounts is one of the most common responsibilities of an IT Help Desk technician.

Typical requests include:

- New employee onboarding
- Password resets
- Locked accounts
- Employee name changes
- Employee offboarding
- Account maintenance

---

# Implementation

## 1. Created User Accounts

Created multiple Active Directory user accounts to simulate an enterprise environment.

Example accounts:

| Name | Username |
|------|----------|
| John Smith | john.smith |
| Sarah Johnson | sarah.johnson |
| Mike Brown | mike.brown |
| Emily Davis | emily.davis |
| Michael Wilson | michael.wilson |
| Olivia Taylor | olivia.taylor |
| Ethan Moore | ethan.moore |
| Sophia White | sophia.white |
| Noah Martin | noah.martin |
| Ava Thomas | ava.thomas |


---

## 2. Disabled and Enabled User Accounts

Disabled selected user accounts to simulate employee leave or termination.

Re-enabled accounts to restore user access.

<img width="754" height="528" alt="01-john smith disabled" src="https://github.com/user-attachments/assets/547c2a94-e296-4c29-a6a7-4479d2d5b0f5" />
<img width="754" height="528" alt="01-john smith enabled" src="https://github.com/user-attachments/assets/2a5adfb4-17d0-4b8b-83d7-5f87f84bfa06" />

---

## 3. Reset User Passwords

Reset passwords for selected users and verified the password reset process.

<img width="754" height="528" alt="03-mike brown password reset" src="https://github.com/user-attachments/assets/247ab250-1a6a-41a6-aaad-109d03c4d316" />
---

## 4. Forced Password Change

Configured users to change their password at the next logon.

This is commonly used after password resets.

<img width="412" height="538" alt="03-mike brown forced reset" src="https://github.com/user-attachments/assets/a2e9560a-1cca-4a7e-be23-4243765bde5c" />

---

## 5. Renamed User Accounts

Modified user account information to simulate employee name changes.

Was Previously Sarah Johnson for reference.

<img width="754" height="528" alt="02-sara miller rename" src="https://github.com/user-attachments/assets/f2f2c0af-2176-495b-a6bb-e9e836f67329" />

---

## 6. Deleted User Accounts

Deleted selected user accounts to simulate employee offboarding.

<img width="751" height="538" alt="04-emily davis deleted" src="https://github.com/user-attachments/assets/10de0238-6ddc-43cc-8c26-1ef06e9aa869" />

---

# Skills Practiced

- Active Directory user administration
- User account creation
- Password management
- Account lifecycle management
- User account maintenance
- Identity administration

---

# Key Concepts Learned

### User Lifecycle Management

User accounts change throughout employment. Administrators must create, modify, disable, and remove accounts while maintaining accurate directory information.

### Password Management

Password resets and forced password changes are among the most common Active Directory tasks performed by help desk technicians.

### Account Administration

Managing account status helps ensure that only authorized users have access to organizational resources.

---

# Outcome

Successfully performed common Active Directory user administration tasks that mirror day-to-day responsibilities in a Windows enterprise environment.

---
