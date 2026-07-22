# Lab 10 – DHCP Administration

## Objective

Configured a DHCP scope on a Windows Server to automate IPv4 address assignment and reviewed core DHCP components, including address pools, leases, reservations, and scope options.

---

## Environment

- Windows Server
- Active Directory Domain Services (AD DS)
- DHCP Server

---

## Tasks Completed

- Verified the DHCP Server role was installed
- Created a new IPv4 DHCP scope
- Configured an IP address range
- Configured subnet mask and lease duration
- Configured DHCP options (default gateway and DNS server)
- Activated the DHCP scope
- Explored the Address Pool, Address Leases, Reservations, and Scope Options

---

## DHCP Scope Configuration

| Setting | Value |
|---------|-------|
| Scope Name | Corporate LAN |
| Start IP | 172.31.11.100 |
| End IP | 172.31.11.200 |
| Subnet Mask | 255.255.255.0 |
| Lease Duration | 8 Days |
| Default Gateway | 172.31.11.1 |
| DNS Server | 172.31.11.72 |
| DNS Domain | devonlab.local |

> **Note:** IP addresses may be partially redacted in screenshots for privacy when publishing this lab to GitHub.

---

## Screenshots

### 1. DHCP Console

<img width="586" height="404" alt="01-DHCP console" src="https://github.com/user-attachments/assets/14adb83d-9fac-42c4-99dc-ff827ca48353" />

---

### 6. Scope Options

<img width="400" height="455" alt="02-scope properties" src="https://github.com/user-attachments/assets/a0b966ca-b2f1-49a0-90d7-2bc3fcfa984c" />

---

## Key Concepts Learned

- Dynamic Host Configuration Protocol (DHCP)
- DHCP Scopes
- Address Pools
- Address Leases
- Reservations
- Scope Options
- Automatic IP Address Assignment
- DHCP and Active Directory Integration

---

## Real-World Scenario

A DHCP scope was configured to automatically assign IPv4 addresses to client devices on the network. The scope included a defined address range, lease duration, default gateway, and DNS server. After activation, the DHCP console was used to verify the scope configuration and review available management options.

---

## Resume Skill

Configured and activated a Windows Server DHCP scope, including IP address ranges, DHCP options, and DNS settings, while validating DHCP configuration through the Windows DHCP management console.
