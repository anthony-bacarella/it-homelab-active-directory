# Active Directory Homelab

This repository documents a hands-on **Active Directory homelab** built to simulate a small business IT environment and common **Tier 1 Help Desk** responsibilities.

The lab focuses on practical, job-relevant Active Directory administration rather than theory, with an emphasis on user lifecycle management, workstation support, cross-platform integration, and ticket-based workflows.

---

## Environment

### Domain
- Active Directory domain: `lab.local`

### Server
- Windows Server 2022  
  - Roles:
    - Domain Controller
    - DNS Server

### Clients
- Windows Server 2022 (domain controller)
- 2 × Windows 10 Enterprise (domain-joined)
- Ubuntu Linux (domain-joined)
- macOS (domain-joined)

### Virtualization / Hardware
- 2 × Windows 11 systems running VirtualBox (used as Windows domain-joined workstations)
- 1 × Ubuntu PC (used as a Linux domain-joined client)
- 1 × macOS laptop (used as a macOS domain-joined client)

---

## What This Lab Demonstrates

This homelab simulates common **Tier 1 Help Desk** and junior IT support tasks, including:

- Active Directory user and computer account management
- Department-based Organizational Unit (OU) design
- Security group creation and membership management
- User onboarding and offboarding workflows
- Password resets and account lockout resolution
- DNS dependency awareness during domain joins
- Group Policy application at a basic level
- Windows workstation deployment and domain joins
- Cross-platform directory integration exposure (Windows, Linux, macOS)
- Ticket-based Help Desk workflows using Jira
- Tier 1 troubleshooting and documentation practices

---

## Ticketing System (Jira)

This lab includes a **Jira-based ticketing system** to simulate real-world Help Desk operations.

Jira is used to demonstrate:
- Incident and service request tracking
- Clear documentation of user issues
- Mapping tickets to Active Directory administrative actions
- Proper resolution and closure of tickets

All tickets are created, worked, and resolved as they would be in a production Help Desk environment.

---

## Tools Used

- Active Directory Users and Computers (ADUC)
- DNS Manager
- Group Policy Management Console (GPMC)
- Jira (Help Desk ticketing simulation)

---

## Repository Structure

- `README.md` – Project overview
- `documentation/`
  - `ad-structure.md` – Active Directory OU, user, group, and computer structure
  - `tier1-activities.md` – Simulated Tier 1 Help Desk tasks and workflows
  - `ticketing-system.md` – Jira ticketing system setup and resolved tickets
  - `screenshots/` – Limited screenshots supporting documentation
- 'ticketing system/'
  - 'README.md'
  - 'screenshots/'   

---

## Purpose

This project demonstrates:
- Understanding of real-world Active Directory administration
- Experience working within a ticket-driven Help Desk environment
- Ability to document and resolve common Tier 1 IT issues
- Readiness for an **entry-level IT Support / Help Desk role**

> Note: This environment uses test accounts and a lab-only domain for demonstration purposes.
