# Microsoft Entra ID (Cloud Identity Management)

This section documents how **Microsoft Entra ID** is used alongside the **lab.local** Active Directory homelab to simulate real-world **cloud identity and access management** tasks commonly handled by **Tier 1 IT Help Desk** and **Junior IT Support** technicians.

The Entra ID lab is used to demonstrate:
- Cloud-based user lifecycle management
- Authentication and sign-in troubleshooting
- Role-Based Access Control (RBAC)
- Identity auditing through sign-in logs
- Understanding of hybrid identity concepts

All actions are performed using **:contentReference[oaicite:0]{index=0} Free** and represent realistic entry-level IT scenarios.

---

## Entra Identity Workflow

Each task follows a structured identity support workflow:
- User request or issue identified
- User or role object reviewed in Entra ID
- Administrative or troubleshooting action performed
- Result verified through sign-in or account status
- Action documented for audit and tracking purposes

---

## Simulated Entra ID Tasks Completed

- **Reset User Password – Jeffery Davis**  
  User reported inability to sign in due to forgotten credentials.  
  Password was reset in Entra ID with enforcement of password change at next sign-in.

- **Sign-In Log Review**  
  Reviewed Entra ID sign-in logs to analyze authentication attempts.  
  Identified successful and failed sign-ins, timestamps, and login activity for troubleshooting purposes.

- **Replicate On-Premises AD Users to Entra ID**  
  Users from the **lab.local** Active Directory environment were manually replicated into Entra ID.  
  This simulates preparation for hybrid identity and cloud migration scenarios.

- **Create Department-Based Groups**  
  Created and managed department groups to reflect organizational structure:
  - Accounting Department  
  - Sales Department  
  - IT Department  
  - Human Resources Department  

  Users were assigned to appropriate groups to demonstrate role separation and least-privilege principles.

- **Assign Administrative Role – Matthew Williams**  
  Assigned the **Global Administrator** role to a designated test account.  
  Role permissions were reviewed to demonstrate understanding of RBAC and privileged access management.

---

## Purpose

This Entra ID lab demonstrates my ability to:
- Perform cloud-based identity administration
- Troubleshoot authentication and login issues
- Analyze sign-in logs for security and access validation
- Apply role-based access control using Entra roles
- Understand hybrid identity concepts between on-prem Active Directory and cloud identity platforms
- Support common Tier 1 Help Desk identity-related requests

---

> Note: All users, roles, and groups are created in a lab environment using test data only. No production accounts or real user data are used.
