## Active Directory Homelab – Tier 1 Help Desk Activities

This homelab simulates common Tier 1 Help Desk tasks in a Windows Active Directory environment, including user lifecycle management, group administration, workstation support, and cross-platform integration.

---

### Administrative Account Management
- Assigned user **Anthony AB. Bacarella** to the **Domain Admin** group
- Demonstrated role-based administrative access and privileged account management
- Simulated adding a help desk technician with elevated permissions
  ![Assigning Group](https://github.com/anthony-bacarella/it-homelab-active-directory/blob/main/screenshots/assigning%20group.png?raw=true)
---

### User Onboarding
- Created a new user account **Jeffery JD. Davis** in the **Sales** OU under the Homelab structure
- Followed organizational naming conventions and proper OU placement
- Simulated onboarding a new employee

---

### User Offboarding / Termination
- Disabled user account **Melissa MS. Smith**
- Moved the account to the **Disabled Users** OU
- Simulated employee termination and access revocation procedures

---

### Account Lockout & Password Reset
- Unlocked user account **Jeffery JD. Davis** after simulated account lockout
- Reset password and enforced password change at next login
- Verified successful authentication following remediation

---

### Security Group Management
- Used Active Directory search functionality (**Find → Users, Contacts, and Groups**) to locate the **SG_IT** security group in `lab.local`
- Added **Anthony AB. Bacarella** as a member of the IT security group
- Demonstrated group-based access management best practices

---

### Windows Workstation Deployment & Domain Join
- Deployed two Windows workstations:
  - **WWS-01**
  - **WWS-02**
- Configured workstation DNS settings to point to the Domain Controller IP address
- Renamed systems according to organizational standards
- Successfully joined both workstations to the Active Directory domain
- Verified domain authentication and computer object creation in Active Directory

---

### Linux (Ubuntu) Remote Access Integration
- Configured Remote Desktop (RDP) access for an Ubuntu user account
- Enabled remote login from Windows domain-joined devices
- Demonstrated basic cross-platform remote access support

---

### macOS Active Directory Integration
- Successfully joined a macOS system to the Active Directory domain
- Verified domain authentication from a non-Windows endpoint
- Demonstrated basic directory integration in a mixed OS environment

---

### Skills Demonstrated
- Active Directory user and computer management
- Employee onboarding and offboarding workflows
- Account lockout resolution and password resets
- Security group search and membership management
- DNS dependency awareness for domain joins
- Windows workstation deployment and support
- Cross-platform integration (Windows, Ubuntu, macOS)
- Tier 1 Help Desk operational troubleshooting
