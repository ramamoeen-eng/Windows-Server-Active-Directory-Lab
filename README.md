
# Windows Server & Active Directory Lab

## Project Overview

This project is a hands-on lab designed to build practical experience in Windows Server administration, Active Directory, DNS, and IT Support operations.

The lab uses VMware Workstation to create an isolated Windows domain environment, simulating real-world IT infrastructure and administration tasks.

## Project Objectives

- Install and configure Windows Server 2022.
- Configure static IP addressing and network settings.
- Understand and implement Active Directory Domain Services (AD DS).
- Configure and manage DNS services.
- Create and manage domain users, groups, and Organizational Units (OUs).
- Join Windows client machines to a domain.
- Implement Group Policy Objects (GPOs).
- Configure shared folders and access permissions.
- Perform administrative tasks using PowerShell.
- Practice troubleshooting common Windows Server and Active Directory issues.

## Lab Environment

### Host Machine

| Component | Specification |
|---|---|
| Laptop | HP ProBook 440 G8 |
| Processor | Intel Core i7-1165G7 |
| RAM | 16 GB |
| Host OS | Windows 10 Pro |
| Virtualization | VMware Workstation Pro 26.0.1 |

### Virtual Machines

| Machine | Operating System | Role |
|---|---|---|
| WS2022-DC01 | Windows Server 2022 Standard Evaluation | Domain Controller (DC) |
| Windows 11 Client | Windows 11 Pro | Domain Client |

### Server Configuration

| Setting | Value |
|---|---|
| Computer Name | DC01 |
| Operating System | Windows Server 2022 Standard Evaluation |
| RAM | 4 GB |
| CPU | 2 Cores |
| Disk | 40 GB |
| Network | VMware Host-only (VMnet1) |
| Static IP | 192.168.170.10 |
| Subnet Mask | 255.255.255.0 |
| Default Gateway | Not configured |

## Technologies & Tools

- Windows Server 2022
- Active Directory Domain Services (AD DS)
- DNS
- Windows 11 Pro
- VMware Workstation Pro
- PowerShell
- TCP/IP Networking
- Group Policy Management
- NTFS Permissions
- VMware Host-only Networking

## Learning Roadmap & Progress

The lab follows a 14-day practical learning plan.

| Day | Topic | Status |
|---|---|---|
| Day 01 | VMware Setup & Windows Server Installation | Completed |
| Day 02 | Initial Server Configuration & Static IP | Completed |
| Day 03 | Windows Server Roles & Features | Pending |
| Day 04 | Active Directory Domain Services Installation | Pending |
| Day 05 | DNS Configuration | Pending |
| Day 06 | Active Directory Users, Groups & OUs | Pending |
| Day 07 | Review, Testing & Documentation | Pending |
| Day 08 | User Account Management | Pending |
| Day 09 | Security Groups & Access Control | Pending |
| Day 10 | Joining Windows 11 Client to the Domain | Pending |
| Day 11 | Group Policy Objects (GPO) | Pending |
| Day 12 | Shared Folders & Permissions | Pending |
| Day 13 | PowerShell Administration | Pending |
| Day 14 | Troubleshooting & Final Review | Pending |

## Repository Structure

```text
Windows-Server-Active-Directory-Lab/
│
├── README.md
│
├── docs/
│   ├── Day-01-VMware-and-Server-Installation.md
│   ├── Day-02-Initial-Server-Configuration.md
│   └── Day-03-Active-Directory-Concepts.md
│
└── screenshots/
    ├── day-01-server-desktop.png
    ├── day-01-server-manager.png
    ├── day-02-hostname-verification.png
    ├── day-02-network-configuration-before.png
    ├── day-02-static-ip-availability-check.png
    ├── day-02-static-ip-configuration-before.png
    ├── day-02-static-ip-verification.png
    ├── day-02-static-ip-ping-test.png
    ├── day-02-network-profile-before.png
    ├── day-02-network-profile-private.png
    └── day-02-dns-configuration-before.png
```

## Practical Skills

Throughout this project, I am developing practical skills in:

- Windows Server installation and configuration.
- Network configuration and TCP/IP troubleshooting.
- Static IP addressing and subnetting.
- Windows Server management using Server Manager.
- PowerShell administration.
- Active Directory infrastructure management.
- DNS and domain name resolution.
- User and group administration.
- Access control and permissions management.
- Group Policy configuration.
- IT infrastructure troubleshooting.

## Documentation

Each lab day includes technical documentation, configuration details, command-line examples, verification results, and screenshots.

All practical tasks and results are documented in the `docs/` and `screenshots/` directories.

## Project Status

**In Progress**

This project is part of my continuous learning journey toward developing practical skills in IT Support, Windows Server Administration, Networking, and Cloud/DevOps infrastructure.

