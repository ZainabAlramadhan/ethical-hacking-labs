# Ethical Hacking Labs

Hands-on labs from my Ethical Hacking course at Imam Abdulrahman Bin Faisal University. They follow the attacker's methodology, from scanning and enumeration to vulnerability assessment, with findings and defensive recommendations for each stage.

> **Note:** All work was performed in isolated virtual lab environments on systems I was authorized to test, for educational purposes only.

## Labs
| # | Lab | Focus | Tools |
|---|---|---|---|
| 02 | [Network Scanning](./02-network-scanning) | Host discovery, port and service scanning, firewall evasion | Nmap |
| 03 | [Enumeration](./03-enumeration) | NetBIOS, SNMP, SMB, FTP, and DNS enumeration | nbtscan, snmp-check, smbclient, dig, dnsenum |
| 04 | [Vulnerability Scanning](./04-vulnerability-scanning) | CWE/CVE/NVD research and OpenVAS assessment | OpenVAS, Docker |

## Lab Environment
- **Attacker:** Kali Linux 2025.3
- **Targets:** Windows 11, Windows Server 2012 R2, Metasploitable 2
- **Platform:** VMware Workstation with isolated NAT networking

## Skills Demonstrated
- Reconnaissance and network scanning with Nmap
- Service enumeration across common Windows and network protocols
- Vulnerability research using CWE, CVE, and NVD
- Vulnerability assessment and severity-based prioritization
- Writing clear findings with remediation recommendations
