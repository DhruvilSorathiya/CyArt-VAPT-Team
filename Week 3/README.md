# Week 3 — Advanced Exploitation and Web Application Security Testing

## Overview
This task focused on performing vulnerability assessment and penetration testing activities in a controlled lab environment using the Metasploitable virtual machine and Damn Vulnerable Web Application (DVWA). The objective was to simulate realistic attacker behavior, identify security weaknesses, and demonstrate exploitation impact across network services and web application components.

## Objectives
- Perform network reconnaissance and service enumeration
- Exploit vulnerable services using known exploits
- Conduct web application security testing
- Demonstrate exploit chaining and system compromise
- Collect and preserve forensic evidence
- Document findings following reporting standards

## Tools and Technologies
- Kali Linux
- Metasploit Framework
- Nmap
- DVWA
- sqlmap
- Netcat
- Wireshark
- Python (PoC customization)

## Activities Performed
- Network scanning to identify exposed services
- Exploitation of vulnerable FTP service (vsftpd backdoor)
- Privilege verification and post-exploitation enumeration
- SQL Injection testing (manual and automated)
- Command Injection leading to reverse shell access
- Cross-Site Scripting validation
- Exploit customization using Python PoC
- Network traffic capture and SHA256 hash verification

## Key Findings
- SQL Injection vulnerability enabling database extraction
- Command Injection allowing remote command execution
- Weak authentication controls permitting unauthorized access
- Reflected Cross-Site Scripting exposing client-side risk
- Successful exploit chaining leading to system compromise

## Deliverables
- Detailed VAPT report
- Evidence screenshots
- Attack path diagram
- Proof-of-concept scripts
- Forensic evidence with integrity verification

## Outcome
The task demonstrated how multiple vulnerabilities can be combined to achieve full system compromise within a controlled environment. The exercise reinforced practical exploitation skills, secure coding awareness, and professional reporting practices aligned with industry penetration testing workflows.

## Demonstration Video
A demonstration of DVWA login bypass showing unauthorized authentication without credentials can be accessed here:

🔗 https://drive.google.com/file/d/1HRzz-74TAxmut0QR3tniUqxYslU9DzER/view?usp=sharing

---
