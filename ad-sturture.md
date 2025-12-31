--

## Users

- User accounts are organized by department (IT, Accounting, Sales)
- Department-based OUs allow targeted Group Policy and access control
- This structure mirrors common enterprise onboarding practices

---

## Groups

- Security groups follow a clear naming convention (`SG_Department`)
- Groups are used to assign permissions rather than assigning permissions directly to users
- Example use cases:
  - File share access
  - Application access
  - Department-level permissions

---

## Computers

- Computer accounts are separated by device type:
  - **Workstations** (desktops)
  - **Laptops** (mobile devices)
- This separation allows different Group Policies based on device usage and security needs

---

## Disabled Objects

- Disabled users and computers are **moved**, not deleted
- Objects are stored in a dedicated **Disabled** OU
- This reflects real-world offboarding and device retirement procedures
- Preserves account history and allows for easy reactivation if required

---

## Purpose of This Structure

This Active Directory layout demonstrates:
- Logical OU design
- Department-based organization
- Proper use of security groups
- Clean handling of disabled accounts
- Understanding of real-world AD administration practices
