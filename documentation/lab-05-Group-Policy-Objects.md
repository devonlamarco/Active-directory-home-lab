# Lab 5 – Group Policy Objects (GPOs)

## Objective

Configured and linked a Group Policy Object (GPO) to an Organizational Unit (OU) in Active Directory to centrally manage Windows settings.

---

## Environment

- Windows Server
- Active Directory Domain Services (AD DS)
- Group Policy Management Console (GPMC)

---

## Tasks Completed

- Created a new Group Policy Object named **IT Workstation Policy**
- Linked the GPO to the **IT** Organizational Unit
- Configured a desktop wallpaper policy
- Configured a policy to prohibit access to Control Panel and PC Settings
- Reviewed the domain password policy in the Default Domain Policy
- Forced a Group Policy refresh using `gpupdate /force`

---

## Screenshots

### 1. GPO linked to the IT OU

<img width="754" height="538" alt="01-IT GPO" src="https://github.com/user-attachments/assets/ce8ec7f1-21f9-4de8-bfb2-13f2038a61e3" />

---

### 2. Desktop Wallpaper Policy Enabled

<img width="686" height="636" alt="02-Desktop policy enabled" src="https://github.com/user-attachments/assets/7b5191cc-c051-49db-bca3-cff41d4a2c0d" />

---

### 3. Control Panel Policy Enabled

<img width="686" height="636" alt="03-control panel policy" src="https://github.com/user-attachments/assets/cf1f30ed-252f-4397-9af9-e58b3abc783b" />

---

### 4. Password Policy (Default Domain Policy)

<img width="787" height="565" alt="04-password policy" src="https://github.com/user-attachments/assets/b80840ee-01a0-472e-b690-bdc2939f50f0" />

---

### 5. Group Policy Update

<img width="979" height="538" alt="05-gpupdate forced" src="https://github.com/user-attachments/assets/f2d6112b-4a26-44b8-9e14-080b7103fb81" />

---

## Key Concepts Learned

- Group Policy Objects (GPOs)
- Organizational Unit (OU) linking
- Centralized Windows management
- User vs Computer Configuration
- Group Policy inheritance
- Domain-wide password policies
- Manual Group Policy updates

---

## Commands Used

```cmd
gpupdate /force
```

---

## Skills Learned

Configured and linked Active Directory Group Policy Objects (GPOs) to centrally manage Windows settings for Organizational Units, including user configuration policies and Group Policy deployment.
