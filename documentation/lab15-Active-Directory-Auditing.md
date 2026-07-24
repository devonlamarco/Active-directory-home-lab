# Lab 15 – Active Directory Auditing & Reporting

## Objective

Performed Active Directory auditing tasks using PowerShell to review user accounts, group memberships, account status, and access information.

---

## Environment

- Windows Server
- Active Directory Domain Services (AD DS)
- Windows PowerShell
- ActiveDirectory PowerShell Module

---

## Tasks Completed

- Generated a list of Active Directory users
- Reviewed enabled and disabled accounts
- Identified inactive accounts
- Audited security group membership
- Exported Active Directory reports to CSV files

---

## Commands Used

```powershell
Get-ADUser -Filter *

Search-ADAccount -AccountDisabled

Search-ADAccount -AccountInactive -TimeSpan 90

Get-ADGroupMember

Export-Csv
```

---

## Screenshots

### 1. Active Directory User Report

<img width="979" height="542" alt="01-User Report" src="https://github.com/user-attachments/assets/39771fff-f262-4bda-96bf-8602d8e13a23" />

---

### 2. Disabled Account Report

<img width="979" height="542" alt="02-Disabled Account" src="https://github.com/user-attachments/assets/2f0dad0d-04fb-4ca8-95fa-24f8baeb25b8" />

---

### 3. Inactive Account Report

<img width="979" height="542" alt="03-Inactive Accounts" src="https://github.com/user-attachments/assets/32bbb6f7-db54-4b8f-8720-1aa6d978416b" />

---

### 4. Security Group Audit

<img width="979" height="542" alt="04-Group Audit" src="https://github.com/user-attachments/assets/435ab36d-7d8b-4dc4-ad8d-7d81223c5780" />

---

### 5. CSV Report Export

<img width="979" height="542" alt="05-csv export" src="https://github.com/user-attachments/assets/850b03a0-c59e-4620-a9a6-324381cb031b" /> <img width="1125" height="634" alt="05-csv verify" src="https://github.com/user-attachments/assets/50164f70-282e-40e2-a041-f832f4740be4" /> <img width="1426" height="752" alt="05-csv opened" src="https://github.com/user-attachments/assets/95862777-c214-4674-b67a-62d13654bd8c" />



---

## Key Concepts Learned

- Identity auditing
- Access reviews
- User lifecycle management
- Security group auditing
- Reporting automation
- Identity governance

---

## Real-World Scenario

Performed an access review similar to an IAM audit by reviewing user accounts, identifying inactive accounts, verifying security group membership, and exporting reports for documentation and compliance purposes.

---

## Resume Skill

Performed Active Directory audits using PowerShell to review account status, security group memberships, and access assignments while generating reports for identity governance processes.
