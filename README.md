# Web Application Security — Lab Portfolio

Twenty-three lab reports from the International Cybersecurity and Digital Forensics Academy (ICDFA), Web Application Security & Digital Forensics phase — modules BVWS101 to BVWS103, completed October 2025 to February 2026. Every report is committed in this repository under [`reports/`](reports/), so the portfolio is fully self-contained.

> **Scope note:** all exercises were performed on ICDFA-authorised lab environments and intentionally vulnerable local targets. No production, third-party or unauthorised system was ever tested.

## Skills & tools

- **Linux system administration:** users and groups, file permissions, process control, Bash scripting and automation
- **Networking:** OSI model, IP addressing and subnetting, reconnaissance and service/vulnerability mapping with nmap
- **Web application security:** OWASP Top 10 exploitation and remediation — SQL injection, XSS, command injection, insecure deserialization, security misconfiguration, sensitive data exposure, logging gaps
- **Lab environments:** Kali Linux, XAMPP web stacks, isolated virtual lab networks

## BVWS101 — Foundations: Linux, Networking & Bash Scripting

| # | Lab | Date | Summary | Report |
|---|-----|------|---------|--------|
| 1 | Basic commands & file system | 2025-10-13 | Core Linux shell navigation and file/directory management, demonstrated hands-on. | [PDF](reports/BVWS101/01-basic-commands-and-filesystem.pdf) |
| 2 | Linux system administration | 2025-10-20 | Configured users, groups, permissions and processes on a Linux host. | [PDF](reports/BVWS101/02-linux-system-administration.pdf) |
| 3 | OSI model cyberlab | 2025-10-27 | Mapped observed network behaviour to OSI layers in a guided cyberlab. | [PDF](reports/BVWS101/03-osi-model-cyberlab.pdf) |
| 4 | IP addressing lab exercise | 2025-10-27 | Calculated and validated IP addressing and subnetting schemes for lab networks. | [PDF](reports/BVWS101/04-ip-addressing-lab.pdf) |
| 5 | Bash scripting lab exercise | 2025-11-03 | Automated routine administration tasks with shell scripts. | [PDF](reports/BVWS101/05-bash-scripting-lab.pdf) |

## BVWS102 — Web Application Security Essentials

| # | Lab | Date | Summary | Report |
|---|-----|------|---------|--------|
| 1 | OSI model cyberlab (web stack) | 2025-10-27 | Applied OSI layering to diagnose a simulated web application stack. | [PDF](reports/BVWS102/01-osi-model-cyberlab.pdf) |
| 2 | Web application security essentials | 2025-11-10 | Core web application security concepts and the failure modes behind them. | [PDF](reports/BVWS102/02-web-application-security-essentials.pdf) |
| 3 | PHP backend development with SQL database | 2025-11-17 | Built a PHP/SQL backend and identified how query handling introduces injection risk. | [PDF](reports/BVWS102/03-php-backend-with-sql-database.pdf) |
| 4 | OWASP Top 10 web vulnerabilities | 2025-11-24 | Mapped the OWASP Top 10 categories to practical lab examples. | [PDF](reports/BVWS102/04-owasp-top-10-overview.pdf) |
| 5 | Virtual lab environment setup | 2025-12-22 | Stood up an isolated virtual lab network for safe web security practice. | [PDF](reports/BVWS102/05-virtual-lab-environment-setup.pdf) |
| 6 | Web application reconnaissance | 2025-12-28 | Performed authorised reconnaissance against lab targets and documented the exposed surface. | [PDF](reports/BVWS102/06-web-application-reconnaissance.pdf) |
| 7 | Nmap mastery and vulnerability mapping | 2026-01-04 | Produced host, service and vulnerability maps with nmap against lab targets. | [PDF](reports/BVWS102/07-nmap-mastery-and-vulnerability-mapping.pdf) |
| 8 | Final project: web application security | 2025-12-04 | End-to-end assessment of a lab web application combining reconnaissance, enumeration and a findings report. | [PDF](reports/BVWS102/08-final-project-web-application-security.pdf) |

## BVWS103 — OWASP Top 10: Vulnerability & Exploitation Techniques

| # | Lab | Date | Summary | Report |
|---|-----|------|---------|--------|
| 1 | XAMPP installation on Kali | 2026-01-22 | Deployed a local vulnerable web stack (XAMPP) as the exploitation target for the module. | [PDF](reports/BVWS103/01-xampp-installation-on-kali.pdf) |
| 2 | HTML injection | 2026-01-25 | Injected HTML into unsanitised input, documented rendering impact and the fix. | [PDF](reports/BVWS103/02-html-injection.pdf) |
| 3 | Advanced SQL injection | 2026-01-25 | Extracted data from a lab application via union- and boolean-based SQL injection. | [PDF](reports/BVWS103/03-advanced-sql-injection.pdf) |
| 4 | Command injection | 2026-01-25 | Achieved OS command execution through unsanitised input and specified input-validation controls. | [PDF](reports/BVWS103/04-command-injection.pdf) |
| 5 | Cross-site scripting (XSS) | 2026-02-01 | Executed reflected and stored XSS payloads and demonstrated cookie-theft impact. | [PDF](reports/BVWS103/05-cross-site-scripting.pdf) |
| 6 | Insecure deserialization | 2026-02-01 | Exploited unsafe object deserialization to alter application behaviour. | [PDF](reports/BVWS103/06-insecure-deserialization.pdf) |
| 7 | Security misconfiguration | 2026-02-01 | Identified and exploited default and misconfigured settings; listed hardening steps. | [PDF](reports/BVWS103/07-security-misconfiguration.pdf) |
| 8 | Sensitive data exposure | 2026-02-08 | Located exposed sensitive data and recommended encryption and access controls. | [PDF](reports/BVWS103/08-sensitive-data-exposure.pdf) |
| 9 | Using components with known vulnerabilities | 2026-02-08 | Exploited a component with published CVEs and documented the patching path. | [PDF](reports/BVWS103/09-known-vulnerable-components.pdf) |
| 10 | Insufficient logging & monitoring | 2026-02-15 | Demonstrated attacker actions escaping detection and specified monitoring improvements. | [PDF](reports/BVWS103/10-insufficient-logging-and-monitoring.pdf) |

## Repository layout

```text
reports/
├── BVWS101/   Linux, networking and Bash foundations (5 reports)
├── BVWS102/   Web application security essentials (8 reports)
└── BVWS103/   OWASP Top 10 exploitation techniques (10 reports)
```

## Related work

- [PortSwigger Web Security Academy writeups](https://github.com/IfyTechy/portswigger-web-security-academy-writeups) — XSS and CSRF lab walkthroughs
- [SBT-DF203 Lab 3 — SYN Flood Attack Investigation Using tshark](https://github.com/IfyTechy/SBT-DF203_Lab3_SYN-Flood-Attack-Investigation-Using-tshark)
- [CIP-B102 Lab 3 — Data Carving with XXD, Binwalk and Scalpel](https://github.com/IfyTechy/CIP-B102_Lab3_Data-Carving-with-XXD-Binwalk-and-Scalpel)

## Author

Nebeuwa Ifeanyichukwu Raphael — digital forensics and cyber-defence trainee, International Cybersecurity and Digital Forensics Academy (ICDFA).
