# 🔐 Week 4 – Advanced Exploitation & Full VAPT Engagement

## 📌 Overview

During Week-4 of the CyArt VAPT internship, I performed multiple hands-on security assessment activities covering advanced exploitation, API security testing, privilege escalation analysis, network protocol attacks, mobile application testing, and a complete end-to-end penetration testing engagement.

The objective of this week was to simulate realistic attacker workflows across diverse attack surfaces while maintaining structured documentation and evidence collection aligned with professional penetration testing practices and the PTES methodology.

---

## 🛠 Tools Used

* Kali Linux
* Nmap
* Metasploit Framework
* Burp Suite
* Postman
* LinPEAS
* Responder
* Ettercap
* Wireshark
* MobSF
* Frida
* OpenVAS (Greenbone GVM)

---

## 🧪 Practical Labs Completed

### 1️⃣ Advanced Exploitation Lab

**Objective:**
Demonstrate multi-stage exploitation workflow and exploit chaining concepts.

**Activities Performed:**

* Performed service enumeration using Nmap
* Identified vulnerable vsftpd 2.3.4 service
* Executed Metasploit exploit module
* Obtained root shell on Metasploitable
* Developed custom buffer overflow PoC
* Demonstrated exploit delivery and validation

**Outcome:**
Successfully simulated host compromise workflow from reconnaissance to post-exploitation and documented exploit chain evidence.

---

### 2️⃣ API Security Testing Lab

**Objective:**
Evaluate API security controls against OWASP API Top 10 risks.

**Activities Performed:**

* Configured Burp Suite interception proxy
* Enumerated application endpoints
* Manipulated request parameters
* Tested authorization controls
* Performed API testing using Postman

**Outcome:**
Identified authorization weaknesses and demonstrated manual API testing methodology with captured evidence.

---

### 3️⃣ Privilege Escalation & Persistence Lab

**Objective:**
Understand post-exploitation enumeration and persistence concepts.

**Activities Performed:**

* Verified user context after exploitation
* Performed system enumeration
* Reviewed privilege boundaries
* Explored persistence mechanisms conceptually

**Outcome:**
Demonstrated escalation awareness and documented persistence workflow concepts.

---

### 4️⃣ Network Protocol Attacks Lab

**Objective:**
Simulate network interception and protocol exploitation techniques.

**Activities Performed:**

* Performed host discovery using Ettercap
* Executed ARP poisoning MitM attack
* Configured DNS spoofing rules
* Captured traffic using Wireshark
* Captured NTLM hashes using Responder

**Outcome:**
Successfully demonstrated network traffic interception, credential capture, and domain redirection scenarios.

---

### 5️⃣ Mobile Application Testing Lab

**Objective:**
Perform static and dynamic mobile application security analysis.

**Activities Performed:**

* Conducted MobSF static APK analysis
* Reviewed permissions and components
* Executed Frida instrumentation script
* Validated runtime hooking capability

**Outcome:**
Identified mobile security risks and confirmed feasibility of dynamic instrumentation.

---

## 🛡 6️⃣ Capstone Project – Full VAPT Engagement

### 🎯 Objective

Conduct a complete penetration testing engagement on a Hack The Box machine and document findings following PTES methodology.

### 🔍 Step 1 – VPN Connection

* Connected to HTB using OpenVPN
* Verified tunnel interface and connectivity

### 🔎 Step 2 – Reconnaissance

* Performed Nmap scan
* Identified Telnet service exposure

### 🧨 Step 3 – Exploitation

* Authenticated to Telnet service
* Obtained root shell
* Retrieved system flag

### 🧪 Step 4 – Vulnerability Assessment

* Executed OpenVAS scan
* Identified information disclosure risks
* Generated vulnerability report

### 🌐 Step 5 – Web/API Validation

* Configured Burp proxy
* Verified traffic interception workflow

---

## 🚨 Key Security Finding

The capstone machine allowed remote administrative login via Telnet, enabling full system compromise due to plaintext credential transmission and lack of access restrictions.

---

## 🛠 Remediation Highlights

* Disable Telnet service
* Replace with SSH
* Restrict remote root login
* Implement firewall controls
* Apply system hardening
* Conduct continuous vulnerability scanning

---

## 📄 Repository Contents

* 📸 Practical screenshots
* 📄 OpenVAS scan report
* 📄 Week-4 VAPT report

---

## 🎯 Learning Outcome

This week strengthened my understanding of:

* Exploitation workflows
* Authorization and privilege risks
* Network interception techniques
* Mobile application security testing
* End-to-end penetration testing methodology
* Professional VAPT reporting practices

The practical simulated a realistic penetration testing engagement from reconnaissance through remediation planning.
