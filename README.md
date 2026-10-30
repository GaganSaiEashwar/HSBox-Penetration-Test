# HSBox – Penetration Testing Report

## Project Overview

This repository contains a penetration testing report documenting an authorized security assessment of the HSBox lab environment.

The assessment covers reconnaissance, service enumeration, web application exploitation, initial access, local enumeration, privilege escalation, and security recommendations.

## Lab Environment

| Parameter | Details |
|---|---|
| Target | HSBox |
| Target IP | 10.0.1.8 |
| Attacker OS | Parrot Security OS |
| Assessment Type | Authorized CTF / Security Lab |

## Methodology

1. Reconnaissance and port scanning
2. Anonymous FTP enumeration
3. Drupal web application enumeration
4. Drupalgeddon exploitation
5. Initial access as `www-data`
6. Local filesystem and SUID enumeration
7. Privilege escalation to root
8. Security findings and remediation recommendations

## Tools Used

- Nmap
- Metasploit Framework
- cURL
- FTP
- Linux command-line utilities
- John the Ripper

## Key Findings

- Vulnerable Drupal web application
- Anonymous FTP access
- Custom SUID binary enabling privilege escalation
- Weak user credentials
- Excessively permissive sudo rules
- Exposed database credentials

## Report

[View the HSBox Penetration Testing Report](./Hsbox_report.html)

## Disclaimer

This assessment was performed in an authorized lab environment for educational and cybersecurity learning purposes. The techniques and findings documented here should only be reproduced on systems for which explicit authorization has been granted.
