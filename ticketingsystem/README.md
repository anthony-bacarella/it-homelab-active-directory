# Ticketing System (Jira)

This section documents how **Jira** is used in the **lab.local** Active Directory homelab to simulate real-world Tier 1 IT Help Desk tickets.

The Jira setup is used to demonstrate:
- Familiarity with ticket-based IT workflows
- Proper documentation of incidents and service requests
- Mapping user requests to Active Directory administrative actions
- End-to-end issue resolution and closure

All tickets represent common scenarios handled by entry-level Help Desk and Desktop Support technicians.

---

## Ticket Workflow

Each ticket follows a standard help desk lifecycle:
- Ticket created (incident or service request)
- Issue reviewed and categorized
- Administrative or troubleshooting action performed
- Resolution documented in Jira
- Ticket marked as resolved

---

## Simulated Tickets Completed

- **Account Locked Out**  
  User account became locked due to repeated failed login attempts.  
  Account was identified and unlocked in Active Directory, restoring user access.

- **Forgot Password**  
  User requested a password reset.  
  Password was reset in Active Directory with enforcement of password change at next logon.

- **Disable User Account – Melissa Smith**  
  Request to disable a former employee’s account.  
  User account was moved to the **Disabled Users** OU and disabled via Active Directory Users and Computers.

- **Connect MacBook to Domain**  
  Request to connect a macOS device to the domain.  
  macOS system was joined to Active Directory and verified for domain authentication.

- **Onboard New Sales User**  
  New hire onboarding request for the Sales department.  
  User account was created in the **Sales OU** and added to the **SG_Sales** security group.

---

## Purpose

This ticketing system demonstrates my ability to:
- Work in a structured, ticket-driven help desk environment
- Resolve common Tier 1 IT issues
- Perform user lifecycle management tasks in Active Directory
- Support both Windows and macOS endpoints
- Properly document and close tickets using Jira

---

> Note: All tickets and user accounts are created in a lab environment using test data only.
