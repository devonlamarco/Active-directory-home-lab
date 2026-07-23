# Lab 12 – Group Policy Troubleshooting & Verification

## Objective

Verified Group Policy configuration and practiced troubleshooting techniques by confirming GPO links, forcing policy updates, and reviewing Group Policy Results.

---

## Environment

- Windows Server
- Active Directory Domain Services (AD DS)
- Group Policy Management Console (GPMC)
- Windows PowerShell / Command Prompt

---

## Tasks Completed

- Verified the **IT Workstation Policy** Group Policy Object existed.
- Confirmed the GPO was linked to the **IT** Organizational Unit.
- Forced a Group Policy update using `gpupdate /force`.
- Generated a Group Policy Results report using `gpresult`.
- Created an HTML Group Policy report for review.
- Investigated why a user-targeted GPO was not visible when logged in as the Domain Administrator.

---

## Commands Used

```cmd
gpupdate /force

gpresult /r

gpresult /h C:\gpresult.html
```

---

## Screenshots

### 1. IT Workstation Policy in Group Policy Objects

<img width="754" height="529" alt="01-IT GPO" src="https://github.com/user-attachments/assets/8b83bb9f-bafe-4ff4-a134-66555f576316" />

---

### 2. IT OU with Linked GPO

<img width="754" height="529" alt="02-IT GPO linked to IT OU" src="https://github.com/user-attachments/assets/2c4e2176-e526-4a47-96a8-e22046f6aaea" />

---

### 3. gpupdate /force Output

<img width="979" height="512" alt="03-gpupdate" src="https://github.com/user-attachments/assets/561f224d-0b45-47a9-ac3f-f7cbd6b134a4" />

---

### 4. gpresult /r Output

<img width="859" height="452" alt="04-gpresult1" src="https://github.com/user-attachments/assets/7f0b226b-652e-4419-bb10-3cb8638073d5" /> <img width="859" height="452" alt="04-gpresult2" src="https://github.com/user-attachments/assets/a977ac86-a814-4913-8337-149b1fe5c5a8" /> <img width="859" height="452" alt="04-gpresult3" src="https://github.com/user-attachments/assets/803c7524-2336-4383-a6fe-c19f5ac38448" />


---

### 5. Group Policy Results Wizard

<img width="520" height="460" alt="05-results wizard" src="https://github.com/user-attachments/assets/445e19a4-96f0-4720-85e3-93a072a5eec0" />

---

### 6. HTML Group Policy Report

<img width="1920" height="1040" alt="06-gpresult html" src="https://github.com/user-attachments/assets/2c880b0d-c664-48bf-9cd7-e9b78e4059d2" />

---

## Key Concepts Learned

- Group Policy Objects (GPOs)
- GPO Linking
- Group Policy Processing
- Resultant Set of Policy (RSoP)
- Group Policy troubleshooting
- gpupdate
- gpresult

---

## Environment Notes

This lab was completed in an AWS-hosted Windows Server environment accessed through Remote Desktop. Because only the built-in Administrator account had logged onto the server, Group Policy Results were only available for that account. User-specific GPO validation would require a separate domain-joined Windows client or an interactive logon from a domain user.

---

## Resume Skill

Verified and troubleshot Active Directory Group Policy Objects (GPOs) by validating policy links, forcing policy updates, and analyzing applied policies using gpresult and the Group Policy Management Console.
