Week 2 - Full VAPT Cycle

## Objective
In this task, I performed a complete Vulnerability Assessment and Penetration Testing (VAPT) cycle in a controlled lab environment.

---

## Environment Setup

- Kali Linux (Attacker)
- Metasploitable2 (Target VM)
- DVWA
- OWASP Juice Shop
- Internal Virtual Network

---

## Workflow Steps

### 1️) Planning & Network Verification
- Verified IP addresses
- Confirmed connectivity using ping

### 2️) Reconnaissance
- Performed Nmap scanning
- Identified open ports and services
- Detected technology stack using WhatWeb

### 3️) Vulnerability Scanning
- Conducted OpenVAS full scan
- Identified critical vulnerabilities
- Validated findings using Nikto

### 4️) Exploitation
- Exploited Apache Tomcat Manager
- Established Meterpreter session
- Verified system access

### 5️) Post-Exploitation
- Switched to shell
- Verified privileges
- Generated SHA256 hash for evidence

### 6️) Web Application Exploitation
- Confirmed SQL Injection manually
- Used sqlmap for database enumeration
- Extracted user credentials
- Cracked password hashes

---

## Deliverables

- VAPT Report (PDF)
- Screenshots of all evidence
- Risk assessment
- Remediation recommendations

---

## Disclaimer
This project was conducted in a controlled lab environment for educational purposes only.
