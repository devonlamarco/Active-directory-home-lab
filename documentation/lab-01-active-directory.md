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

![AWS EC2 Instance](../screenshots/01-aws-ec2-instance.png)

---

## 2. Installed Active Directory Domain Services

Installed the Active Directory Domain Services (AD DS) server role through Server Manager.

This role allows Windows Server to function as a Domain Controller.

![AD DS Installation](../screenshots/02-ad-ds-installed.png)

---

## 3. Created Active Directory Domain

Promoted the Windows Server instance to a Domain Controller and created the Active Directory forest:

```text
devonlab.local
```

The Domain Controller provides centralized authentication and stores user, computer, and group objects.

![Active Directory Users and Computers](../screenshots/03-active-directory-users.png)

---

## 4. Verified DNS Configuration

Verified that DNS was configured for the Active Directory domain.

Active Directory relies on DNS so domain-joined computers can locate Domain Controllers.

![DNS Manager](../screenshots/04-dns-manager.png)

---

## 5. Verified Administrative Tools

Verified access to common Windows administration tools:

- Active Directory Users and Computers
- DNS Manager
- Group Policy Management

![Server Manager Tools](../screenshots/05-server-manager-tools.png)

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
