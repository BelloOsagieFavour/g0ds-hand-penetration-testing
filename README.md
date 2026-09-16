# g0ds-Hand Penetration Testing

## Project Overview

This repository contains my penetration testing assessment of the **g0ds-Hand** vulnerable machine. The assessment documents network discovery, host verification, port and service enumeration, web application enumeration, vulnerability research, exploitation validation, and post-exploitation activities against the EyesOfNetwork application.

## Assessment Type

- **Target:** g0ds-Hand
- **Assessment:** Internal Network Penetration Test
- **Primary Application:** EyesOfNetwork
- **Risk Rating:** High

## Methodology

1. Network Discovery — `arp-scan`
2. Host Verification — `fping`
3. Port and Service Enumeration — `nmap`
4. Web Application Enumeration
5. Vulnerability Research — `searchsploit`
6. Metasploit Initialization — `msfconsole`
7. Module Discovery — `search eye`
8. Exploit Module Result / Selection
9. Exploit Selection — `use 16`
10. Module Information Review — `info`
11. Target Configuration — `set RHOSTS`
12. Local Host Configuration — `set LHOST`
13. Exploitation — `exploit`
14. Post-Exploitation Enumeration — `ls`
15. Working Directory Verification — `pwd`
16. Proof of Access — `getuid`

## Tools Used

- Kali Linux
- arp-scan
- fping
- Nmap
- SearchSploit
- Metasploit Framework
- Meterpreter
- Web Browser

## Evidence

The `screenshots/` directory contains the evidence images extracted from the original assessment document and renamed according to the actual sequence shown in the report.

| Step | Evidence |
|---|---|
| 1 | [Network Discovery — ARP Scan](screenshots/01-network-discovery-arp-scan.png) |
| 2 | [Host Verification — fping](screenshots/02-host-verification-fping.png) |
| 3 | [Port and Service Enumeration — Nmap](screenshots/03-port-service-enumeration-nmap.png) |
| 4 | [Web Application Enumeration](screenshots/04-web-application-enumeration.png) |
| 5 | [Vulnerability Research — SearchSploit](screenshots/05-vulnerability-research-searchsploit.png) |
| 6 | [Metasploit Initialization](screenshots/06-metasploit-initialization.png) |
| 7 | [Module Discovery — search eye](screenshots/07-module-discovery-search-eye.png) |
| 8 | [Module Discovery Results](screenshots/08-module-discovery-results.png) |
| 9 | [Exploit Selection — use 16](screenshots/09-exploit-selection.png) |
| 10 | [Module Information — info](screenshots/10-module-information-info.png) |
| 11 | [Target Configuration — RHOSTS](screenshots/11-target-configuration-rhosts.png) |
| 12 | [Local Host Configuration — LHOST](screenshots/12-local-host-configuration-lhost.png) |
| 13 | [Exploitation](screenshots/13-exploitation.png) |
| 14 | [Post-Exploitation — ls](screenshots/14-post-exploitation-ls.png) |
| 15 | [Working Directory — pwd](screenshots/15-working-directory-pwd.png) |
| 16 | [Proof of Access — getuid](screenshots/16-proof-of-access-getuid.png) |

The report in `report/` is the original report converted to PDF so that its screenshots remain attached to the documented steps.

## Report

[Open the full penetration testing report](report/g0ds-hand-penetration-testing-report.pdf)

## Key Findings

- Vulnerable EyesOfNetwork application identified
- Publicly available exploit discovered
- Remote Code Execution successfully validated
- Unauthorized access to target files documented

## Recommendations

- Update EyesOfNetwork to the latest supported version.
- Apply security patches promptly.
- Restrict access to administrative interfaces.
- Implement network segmentation where appropriate.
- Perform regular vulnerability assessments.
- Enable centralized logging and monitoring.
- Review web application security configurations periodically.

## Disclaimer

This project was performed in a controlled cybersecurity lab environment for educational and portfolio purposes. Testing should only be conducted against systems for which authorization has been provided.

## Author

**BELLO OSAGIE FAVOUR**
