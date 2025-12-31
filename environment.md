# Active Directory Homelab Environment

## Domain Name
- **lab.local**

## Server Roles
- **Windows Server 2022**
  - Active Directory Domain Services (AD DS)
  - DNS Server
  - Group Policy Management

## Workstation Operating Systems
- **Windows 10 Enterprise** (Domain-joined client)
- **Ubuntu Linux** (Domain-joined using Kerberos/SSSD)
- **macOS** (Planned domain integration)

## Virtualization & Networking
- **VirtualBox**
  - Internal Network for isolated domain environment

## Tools Used
- **Active Directory Users and Computers (ADUC)**
- **DNS Manager**
- **Group Policy Management Console (GPMC)**
- **PowerShell**
- **Spiceworks** (Ticketing system for help desk simulations)

## Purpose of Environment
This homelab simulates a small corporate IT environment to practice and demonstrate:
- User and group administration
- Password resets and account lockouts
- DNS configuration and troubleshooting
- Group Policy creation and enforcement
- Tier 1 / Tier 2 Help Desk workflows
- Cross-platform domain authentication
