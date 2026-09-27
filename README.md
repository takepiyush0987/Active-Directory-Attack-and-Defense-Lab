# Active Directory Attack & Defense Lab

A hands-on cybersecurity project focused on building, enumerating,
assessing, attacking, monitoring, hardening, and re-testing an
isolated Active Directory environment.

## Lab Environment

- Windows Server 2022 — Domain Controller
- Windows 11 — Domain Client
- Kali Linux — Security Testing
- Oracle VirtualBox
- Host-only isolated network
- Domain: cyberlab.local

## Architecture

| Machine | Role | IP |
|---|---|---|
| DC01 | Domain Controller | 192.168.56.103 |
| Client01 | Domain Client | 192.168.56.104 |
| Kali | Security Testing | 192.168.56.102 |

## Methodology

Identify → Enumerate → Assess → Simulate Attack
→ Detect → Remediate → Verify

## Key Areas

- Active Directory & AD DS
- DNS
- Kerberos
- LDAP
- SMB
- SPN enumeration
- Group Policy
- ACL & AdminSDHolder
- Authentication
- Security auditing
- Event monitoring
- Hardening & verification

## Project Report

[Download the Complete Project Report](./Active_Directory_Attack_and_Defense_Lab.pdf)

## Evidence

Screenshots and command outputs are available in the
`screenshots/` directory.

## Disclaimer

This project was performed in an isolated, intentionally
configured lab environment for educational and defensive
cybersecurity purposes.
