# Basic-Employee-Onboarding-AD-RBAC-
Active Directory infrastructure rebuild for a fictional company called “Northstar Medical Group”. Includes domain setup, organizational structure, user provisioning, RBAC implementation, and incident resolution.


## Problem Statement
Northstar Medical Group had a disorganized Active Directory environment. Users would typically get added manually, and that led to the MSP forgetting to disable their accounts for months, which is a HIPAA risk. Access was very inconsistent, and some people had more permissions than they should have.

## Solution Overview
Built an Active Directory environment for Northstar Medical Group (NMG) using the `NMG.com` domain. Created four Organizational Units (OUs) and corresponding security groups to organize users and manage access. Provisioned user accounts and assigned group memberships based on role-based access control (RBAC) principles, ensuring users received access aligned with their job responsibilities.

## Video Walkthrough
[(https://www.loom.com/share/f680a82254804f469613c4a10780efb0)](https://www.loom.com/share/6c35df79f1fc4bb4a79b2d1d66fc421d)

## Tools Used
* Windows Server
* Active Directory Domain Services
* VirtualBox
* UTM
* RBAC
* GitHub

## Project Timeline
* Day 1: Domain creation and domain controller promotion
* Day 2: Organizational unit and security group design
* Day 3: User provisioning and RBAC implementation
* Day 4: Incident response and resolution (NMG-0047)
* Day 5: Documentation and case study packaging

## Key Accomplishments
* Built NMG.com domain from scratch
* Designed department-based OU structure (Finance, HR, IT, Operations)
* Implemented RBAC with security groups mapped to each department
* Provisioned 15 user accounts with consistent naming conventions and attribute standards
* Diagnosed and resolved a multi-cause access issue (wrong OU + missing group membership)
* Documented full incident resolution with root cause analysis

## Repository Structure
* Documentation: domain setup notes, OU and security groups, user list, RBAC structure
* Incident-Reports: Resolution to Incident ticket
* Screenshots: Images of the project from start to finish

