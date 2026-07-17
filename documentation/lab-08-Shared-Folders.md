# Lab 8 – Shared Folders & Share Permissions

## Objective

Configured Windows SMB shares for departmental folders and assigned Share Permissions using Active Directory security groups. Compared Share Permissions with NTFS permissions to understand effective access.

---

## Environment

- Windows Server
- Active Directory Domain Services (AD DS)
- SMB File Sharing

---

## Tasks Completed

- Shared departmental folders using Advanced Sharing
- Configured Share Permissions
- Assigned department security groups to network shares
- Reviewed NTFS permissions
- Compared Share and NTFS permissions
- Verified SMB shares using Computer Management

---

## Folder Structure

```text
C:\CompanyData
├── IT
├── HR
├── Accounting
└── Sales
```

---

## Screenshots

### 1. Department Folder Structure

<img width="1125" height="634" alt="01-Companydata folder" src="https://github.com/user-attachments/assets/04465811-c720-4eb0-84eb-611fa6fdbefa" />

### 2. IT Advanced Sharing

<img width="351" height="363" alt="02-adv sharing" src="https://github.com/user-attachments/assets/f10a79f8-7d9b-4e80-91e4-0d976cb64a89" />

### 3. IT Share Permissions

<img width="363" height="450" alt="03-share perms" src="https://github.com/user-attachments/assets/ae32b8f3-d62c-479c-902f-4983c5493b54" />

### 4. Accounting Share Permissions

<img width="363" height="450" alt="04-accounting share perms" src="https://github.com/user-attachments/assets/e80b31d4-2635-4bd0-b421-700d5e48caa5" />

### 5. Shared Folders Console

<img width="986" height="702" alt="05-Shared folders console" src="https://github.com/user-attachments/assets/13578619-b1f3-4405-97bd-449c4c60c605" />

### 6. NTFS Permissions

<img width="363" height="481" alt="06-NTFS perms" src="https://github.com/user-attachments/assets/03e3a77c-64e2-4984-816a-3891ab5c62b5" />

---

## Key Concepts Learned

- SMB File Sharing
- Share Permissions
- NTFS Permissions
- Effective Permissions
- Active Directory Security Groups
- Least Privilege

---

## Real-World Scenario

A user reported that they could access a departmental share but could not save files. The issue was investigated by reviewing both Share Permissions and NTFS permissions to determine the user's effective access.

---

## Resume Skill

Configured Windows SMB shares and Share Permissions using Active Directory security groups while implementing least-privilege access to departmental resources.
