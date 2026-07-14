# Lab 1 - Building an Active Directory Domain Controller

## Objective

The goal of this lab was to deploy a Windows Server 2022 environment in AWS and configure it as an Active Directory Domain Controller.

This lab provided hands-on experience with:

- Windows Server administration
- Active Directory Domain Services (AD DS)
- Domain Controllers
- DNS configuration
- Identity management concepts

---

# Environment

## Infrastructure

- Cloud Provider: Amazon Web Services (AWS)
- Virtual Machine: Windows Server 2022
- Server Name: DC01
- Domain Name: devonlab.local

---

# Lab Overview

The following environment was created:

```text
AWS EC2 Instance

        |

Windows Server 2022

        |

Active Directory Domain Services

        |

Domain Controller

        |

devonlab.local
```

---

# Implementation Steps

## 1. Created Windows Server Instance

Created a Windows Server 2022 EC2 instance in AWS.

The server was configured with Remote Desktop access for administration.


---

## 2. Installed Active Directory Domain Services

Installed the Active Directory Domain Services (AD DS) server role through Server Manager.

This role allows Windows Server to function as a Domain Controller.


---

## 3. Created Active Directory Domain

Promoted the Windows Server instance to a Domain Controller and created the Active Directory forest:

```text
devonlab.local
```

The Domain Controller provides centralized authentication and stores user, computer, and group objects.


---

## 4. Verified DNS Configuration

Verified that DNS was configured for the Active Directory domain.

Active Directory relies on DNS so domain-joined computers can locate Domain Controllers.


---

## 5. Verified Administrative Tools

Verified access to common Windows administration tools:

- Active Directory Users and Computers
- DNS Manager
- Group Policy Management


---

# Skills Practiced

- AWS EC2 deployment
- Windows Server 2022 administration
- Active Directory Domain Services
- Domain Controller configuration
- DNS management
- Remote Desktop administration

---

  - Account unlocks
  - User provisioning
  - Access management
---
## 6. Screenshots
01-aws-ec2-instance
<img width="1920" height="1032" alt="01-aws-ec2-instance" src="https://github.com/user-attachments/assets/4ac825eb-17db-43c1-a56c-1d976bee0c46" />
02-Server-Manager-Dashboard
<img width="1920" height="1040" alt="02-Server-Manager-Dashboard" src="https://github.com/user-attachments/assets/6c442a26-2f92-4c8c-bd25-931c819cb001" />
03-AD-Users-and-Cpus-devonlab.local-expanded
<img width="1152" height="648" alt="03-AD-Users-and-Cpus devonlab local expanded" src="https://github.com/user-attachments/assets/35ac1ac5-99af-43d7-80a1-c797a91778c3" />
04-DNS-Manager-devonlab

<img width="754" height="528" alt="04-DNS-Manage-devonlab" src="https://github.com/user-attachments/assets/a3556f37-4c34-43e3-bfef-720b118b489e" />

05-server-Manager-Tools

<img width="364" height="666" alt="05-Server-Manager-Tools" src="https://github.com/user-attachments/assets/8457f27a-1136-4f88-b9bf-23f61c95e73d" />


