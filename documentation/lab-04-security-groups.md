# Lab 4 - Active Directory Security Groups

## Objective

The goal of this lab was to create and manage Active Directory Security Groups to simulate role-based access control (RBAC) used in enterprise Windows environments.

This lab focused on managing authorization through group membership rather than assigning permissions directly to individual users.

---

# Environment

## Infrastructure

- Cloud Provider: Amazon Web Services (AWS)
- Operating System: Windows Server 2022
- Domain: devonlab.local
- Management Tool: Active Directory Users and Computers (ADUC)

---

# Why Security Groups?

Enterprise environments use Security Groups to simplify permission management.

Instead of assigning permissions directly to users, administrators assign permissions to groups and add users to those groups. This approach is easier to manage and scales much better in large organizations.

---

# Implementation

## 1. Created Security Groups

Created the following Global Security Groups:

- Sales_Read
- Accounting_RW
- HR
- VPN_Users
- Remote_Desktop_Users

<img width="754" height="538" alt="01-security groups" src="https://github.com/user-attachments/assets/58d21ad5-0621-4518-b237-811518caee95" />

---

## 2. Assigned Users to Groups

Added users to their appropriate Security Groups based on department or role.

<img width="755" height="538" alt="02-john smith accounting" src="https://github.com/user-attachments/assets/1094767e-1ea6-413e-97ef-3617db9c9839" />

---

## 3. Verified Group Membership

Verified user memberships using the **Member Of** tab.

<img width="752" height="611" alt="02-john smith verified" src="https://github.com/user-attachments/assets/24592714-598b-49be-963a-9a4982332618" />

---

## 4. Updated Group Membership

Removed users from one group and added them to another to simulate a departmental transfer.

<img width="752" height="594" alt="02-john smith switch" src="https://github.com/user-attachments/assets/97dad283-4e34-451d-92c6-f32cc40b2b23" />
---

# Skills Practiced

- Creating Security Groups
- Managing group membership
- Active Directory authorization
- Role-Based Access Control (RBAC)
- User access management

---

# Outcome

Successfully implemented Security Groups to manage user access using role-based administration, following enterprise Active Directory best practices.

---
