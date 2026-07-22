# DevonLab Active Directory Home Lab

A hands-on Windows Server Active Directory environment built in AWS.

## Completed Labs

### Lab 1 - Active Directory Domain Controller

Built a Windows Server 2022 Domain Controller environment.

Skills demonstrated:

- AWS EC2 deployment
- Windows Server administration
- Active Directory Domain Services
- DNS configuration
- Domain Controller setup

Documentation:

[Lab 1 Documentation](documentation/lab-01-active-directory.md)

## Lab 2 – Organizational Units (OUs)

Built a logical Active Directory organizational structure by creating departmental Organizational Units (OUs), creating user accounts, and organizing users into their respective departments.

**Skills demonstrated:**

- Active Directory administration
- Organizational Unit (OU) creation
- User account creation
- User object management
- Active Directory organization
- Basic identity administration

**Key concepts:**

- Organizational Units (OUs)
- Delegation of administration
- Departmental organization
- Enterprise Active Directory structure

**Documentation:**

[Lab 2 Documentation](documentation/lab-02-organizational-units.md)

## Lab 3 – User Administration

Performed common Active Directory user management tasks to simulate daily help desk operations.

**Skills demonstrated:**

- User account creation
- Password management
- Account enable/disable
- Password resets
- Forced password changes
- User account lifecycle management

**Key concepts:**

- Identity administration
- User lifecycle management
- Account maintenance
- Help desk workflows

**Documentation:**

[Lab 3 Documentation](documentation/lab-03-user-administration.md)

## Lab 4 – Security Groups

Created and managed Active Directory Security Groups to simulate enterprise authorization and role-based access control (RBAC).

**Skills demonstrated:**

- Security Group creation
- Group membership management
- User authorization
- Active Directory administration
- Role-based access control (RBAC)

**Key concepts:**

- Authentication vs. Authorization
- Security Groups
- Least privilege
- Access management

**Documentation:**

[Lab 4 Documentation](documentation/lab-04-security-groups.md)

## Lab 5 – Group Policy Objects (GPOs)

**Skills Practiced**

- Created and linked Group Policy Objects (GPOs)
- Applied user configuration policies
- Configured desktop and Control Panel restrictions
- Reviewed domain password policies
- Forced Group Policy updates
- Learned Group Policy inheritance and centralized management

**Technologies**

- Active Directory
- Group Policy Management Console (GPMC)
- Windows Server

**Documentation**

📄 [Lab 5 – Group Policy Objects](documentation/lab-05-Group-Policy-Objects.md)

## Lab 6 – Delegation of Control

**Skills Practiced**

- Created a HelpDesk security group
- Delegated administrative permissions
- Applied the Principle of Least Privilege
- Assigned password reset permissions
- Reviewed delegated permissions on an Organizational Unit

**Technologies**

- Active Directory Users and Computers
- Active Directory Domain Services (AD DS)
- Delegation of Control Wizard

**Documentation**

📄 [Lab 6 – Delegation of Control](documentation/lab-06-Delegation-of-Control.md)

## Lab 7 – NTFS Permissions

**Skills Practiced**

- Configured NTFS folder permissions
- Applied security groups to file system resources
- Disabled and managed permission inheritance
- Implemented role-based access control (RBAC)
- Applied least-privilege principles

**Technologies**

- Windows Server
- Active Directory
- NTFS File System

**Documentation**

📄 [Lab 7 – NTFS Permissions](documentation/lab-07-NTFS-Permissions.md)

## Lab 8 – Shared Folders & Share Permissions

**Skills Practiced**

- Configured SMB network shares
- Assigned Share Permissions using Active Directory groups
- Compared Share Permissions with NTFS permissions
- Verified shared folders using Computer Management
- Applied least-privilege access control

**Technologies**

- Windows Server
- Active Directory
- SMB File Sharing
- NTFS

**Documentation**

📄 [Lab 8 – Shared Folders & Share Permissions](documentation/lab-08-Shared-Folders.md)

## Lab 9 – DNS Administration

**Skills Practiced**

- Managed Active Directory-integrated DNS
- Created A and CNAME records
- Verified DNS resolution with nslookup
- Explored Forward Lookup Zones
- Reviewed SRV records used by Active Directory

**Technologies**

- Windows DNS
- Active Directory
- nslookup

**Documentation**

📄 [Lab 9 – DNS Administration](documentation/lab-09-DNS-Administration.md)

## Lab 10 – DHCP Administration

**Skills Practiced**

- Configured a Windows DHCP scope
- Assigned IP address ranges
- Configured DHCP options (gateway and DNS)
- Reviewed address pools, leases, and reservations
- Activated and verified DHCP services

**Technologies**

- Windows Server
- DHCP Server
- Active Directory

**Documentation**

📄 [Lab 10 – DHCP Administration](documentation/lab-10-DHCP-Administration.md)

## Lab 11 – Active Directory PowerShell

**Skills Practiced**

- Used PowerShell to manage Active Directory objects
- Queried domain and user information
- Retrieved user group memberships
- Created and verified Active Directory user accounts
- Added users to security groups using PowerShell
- Practiced identity lifecycle tasks similar to user onboarding

**Technologies**

- Windows PowerShell
- Active Directory Domain Services (AD DS)
- ActiveDirectory PowerShell Module

**Tasks Completed**

- Imported the ActiveDirectory PowerShell module
- Retrieved domain information using PowerShell
- Queried Active Directory users
- Verified security group memberships
- Created a new Active Directory user
- Assigned access through security group membership

**Real-World Scenario**

Simulated a new employee onboarding request by creating an Active Directory account and assigning access based on the employee's department and job responsibilities.

Example workflow:

```
HR Request
    ↓
Create AD User Account
    ↓
Assign Security Groups
    ↓
User Receives Required Access
```

**Documentation**

📄 [Lab 11 – Active Directory PowerShell](documentation/lab-11-Active-Directory-Powershell.md)
