# Lab 2 - Creating Organizational Units (OUs)

## Objective

The goal of this lab was to organize an Active Directory environment by creating Organizational Units (OUs) for different company departments.

This lab provided hands-on experience with:

- Active Directory organization
- Organizational Unit (OU) creation
- User administration
- Moving users between OUs
- Active Directory best practices

---

# Environment

## Infrastructure

- Cloud Provider: Amazon Web Services (AWS)
- Operating System: Windows Server 2022
- Domain: devonlab.local
- Management Tool: Active Directory Users and Computers (ADUC)

---

# Why Organizational Units?

Organizational Units allow administrators to logically organize users, computers, and other Active Directory objects.

A typical company may separate departments into different OUs to simplify administration, apply Group Policies, and delegate management responsibilities.

---

# Organizational Structure

The following Organizational Units were created:

```text
devonlab.local
│
├── Accounting
├── HR
├── IT
└── Sales
```

---

# Implementation Steps

## 1. Created Organizational Units

Created the following Organizational Units within the root of the Active Directory domain:

- Accounting
- Sales
- HR
- IT

---

## 2. Created Test User Accounts

Created four user accounts to simulate employees within an organization.

| Name | Username |
|------|----------|
| John Smith | john.smith |
| Sarah Johnson | sarah.johnson |
| Mike Brown | mike.brown |
| Emily Davis | emily.davis |

---

## 3. Organized Users into Departments

Moved each user into the appropriate Organizational Unit.

| User | Organizational Unit |
|------|----------------------|
| John Smith | Accounting |
| Sarah Johnson | HR |
| Mike Brown | IT |
| Emily Davis | Sales |

### Accounting

<img width="754" height="528" alt="01-john-smith-accounting" src="https://github.com/user-attachments/assets/4ed3b25a-b1dd-45fa-9a2b-cf68bd5ed22f" />

### HR

<img width="754" height="528" alt="03-sarah-johnson-hr" src="https://github.com/user-attachments/assets/709710f1-6fa5-4ce1-b2ec-6b37b69c5515" />

### IT

<img width="754" height="528" alt="04-mike-brown-it" src="https://github.com/user-attachments/assets/a539745c-9343-468b-b194-46cf89b94e5e" />

### Sales

<img width="754" height="528" alt="02-emily-davis-sales" src="https://github.com/user-attachments/assets/8b041121-cad1-4162-bfb5-242a7f26e66f" />

---

# Skills Practiced

- Creating Organizational Units (OUs)
- Active Directory administration
- Creating user accounts
- Moving users between OUs
- Organizing Active Directory objects
- Using Active Directory Users and Computers (ADUC)

---

# Key Concepts Learned

### Organizational Units

Organizational Units provide a logical way to organize Active Directory objects. They make large environments easier to manage and allow administrators to apply policies or delegate management to specific departments.

### Delegation

OUs make it possible to grant administrative permissions over a single department without giving full administrative access to the entire domain.

### Administration

Grouping users by department simplifies common help desk tasks such as locating user accounts, resetting passwords, and managing access.

---

# Outcome

Successfully created a departmental OU structure within Active Directory, created user accounts, and organized those users into their appropriate departments to simulate a real-world enterprise environment.

---
