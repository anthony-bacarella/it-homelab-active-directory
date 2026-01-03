# Microsoft Entra ID (Azure AD) Homelab

This project documents hands-on experience administering a **Microsoft Entra ID (Azure Active Directory)** tenant to simulate real-world **Tier 1 IT Help Desk** and **identity management** tasks in a cloud environment.

The lab focuses on **user lifecycle management, authentication troubleshooting, role-based access control (RBAC), and hybrid identity concepts**, using **Microsoft Entra Free**.

---

## Environment Overview

- **Platform:** Microsoft Entra ID (Free Tier)
- **Tenant Type:** Cloud-only Entra tenant
- **Identity Source:** Simulated on-premises Active Directory users (manually replicated)
- **Licensing:** Entra ID Free (no Premium features used)

---

## Objectives

- Demonstrate core cloud identity administration skills
- Simulate common Tier 1 help desk identity-related tickets
- Understand Entra ID structure and role-based permissions
- Show readiness for Microsoft 365 / IAM environments

---

## Users

The following users were created in Entra ID to mirror an on-premises Active Directory environment:

- Jeffery Davis  
- Matthew Williams  
- Additional department-based users (Accounting, Sales, IT, HR)

User objects were created to reflect real organizational structure and role separation.

---

## Tasks Performed

### 1️⃣ User Password Reset & Account Support

- Performed password reset for **Jeffery Davis**
- Forced password change at next sign-in
- Verified successful login after reset

**Skills Demonstrated**
- Tier 1 identity troubleshooting  
- User lifecycle management  
- End-user support workflows  

---

### 2️⃣ Sign-In Log Review & Troubleshooting

- Reviewed Entra ID sign-in logs
- Identified:
  - Successful logins
  - Failed authentication attempts
  - Login source and timestamps

**Skills Demonstrated**
- Authentication troubleshooting  
- Security awareness  
- Audit log analysis  

---

### 3️⃣ On-Premises AD User Replication (Conceptual Hybrid Identity)

- Replicated on-premises Active Directory users into Entra ID
- Maintained consistent:
  - Usernames
  - Department structure
  - Role alignment

**Purpose**
- Simulate hybrid identity preparation
- Demonstrate understanding of cloud transition planning

**Note**
> This lab intentionally avoids Entra Connect to remain within free licensing constraints.

---

### 4️⃣ Department-Based Group Management

Created and managed security groups to represent organizational departments:

- Accounting Department  
- Sales Department  
- IT Department  
- Human Resources Department  

Users were assigned to appropriate groups to demonstrate **logical access structuring** and **least-privilege principles**.

**Skills Demonstrated**
- Group-based access planning  
- Organizational identity design  
- Role separation  

---

### 5️⃣ Role-Based Access Control (RBAC)

- Assigned **Matthew Williams** the **Global Administrator** role
- Evaluated role permissions and scope

**Security Best Practice**
- Global Administrator role assigned to a single test account
- Standard users maintained least-privilege access

**Skills Demonstrated**
- RBAC fundamentals  
- Privileged account awareness  
- Administrative role separation  

---

## Real-World Scenarios Simulated

- User unable to log in → password reset and verification  
- Investigating failed sign-in attempts  
- Structuring users and departments in a cloud directory  
- Assigning administrative privileges securely  

---

## Tools Used

- Microsoft Entra Admin Center  
- Entra ID Users & Groups  
- Sign-In Logs  
- Role Management  

---

## Key Takeaways

This lab demonstrates practical experience with:

- Cloud identity administration
- User authentication troubleshooting
- Role-based access control
- Hybrid identity concepts
- Tier 1 IT Help Desk workflows

---

## Next Steps

Planned enhancements may include:
- Guest user access simulation
- Expanded role comparison documentation
- Microsoft 365 integration (when licensing permits)

---

## Screenshots

Screenshots are stored in the `/screenshots` directory and include:

- User password reset workflow  
- Sign-in log review  
- Group membership assignments  
- Role assignment confirmation  

(1–2 screenshots per task to maintain clarity and professionalism)

---

## Author

**Anthony Bacarella**  
Entry-Level IT Support / Help Desk Candidate  
Hands-on experience with Active Directory, Microsoft Entra ID, and cloud identity management
