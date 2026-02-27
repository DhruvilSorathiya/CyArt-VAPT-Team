🔐 Week 4 – Full VAPT Practical Implementation
📌 Overview
In Week 4, I performed multiple hands-on security labs focused on advanced exploitation, API testing, privilege escalation, network attacks, mobile testing, and a complete end-to-end VAPT engagement.
This week emphasized practical execution, structured documentation, and professional reporting aligned with PTES methodology. I used industry-standard tools and simulated real-world penetration testing scenarios in controlled lab environments.

🛠 Tools Used
Kali Linux
Nmap
Metasploit Framework
OpenVAS (Greenbone GVM)
Burp Suite
Postman
LinPEAS
Responder
Ettercap
Wireshark
MobSF
Frida

🧪 Practical Labs Completed

1️⃣ Advanced Exploitation Lab
Objective:
Simulate multi-stage exploitation and understand exploit chaining.
Activities Performed:
Used Metasploit to execute remote exploitation modules.
Simulated multi-step attack flow.
Analyzed exploit payload behavior.
Reviewed RCE-based attack patterns.
Documented exploit ID, target IP, payload type, and status.
Outcome:
Successfully demonstrated exploit execution flow and documented attack chain logic with screenshots.

2️⃣ API Security Testing Lab
Objective:
Test APIs against OWASP API Top 10 vulnerabilities.
Activities Performed:
Intercepted API traffic using Burp Suite.
Manipulated API tokens to test authorization controls.
Enumerated endpoints.
Tested for Broken Object Level Authorization (BOLA).
Attempted injection-based payload testing.
Logged vulnerability ID, severity, and target endpoints.
Created API testing checklist documentation.
Outcome:
Identified authorization weaknesses and documented manual API testing methodology with screenshots.

3️⃣ Privilege Escalation & Persistence Lab
Objective:
Identify escalation vectors and simulate persistence mechanisms.
Activities Performed:
Performed system enumeration.
Identified SUID-based privilege escalation paths.
Simulated privilege escalation to elevated access.
Demonstrated persistence mechanism using scheduled task concept.
Logged technique, target IP, and final outcome.
Outcome:
Successfully simulated root-level escalation scenario and documented persistence workflow.

4️⃣ Network Protocol Attacks Lab
Objective:
Simulate protocol-based attack techniques.
Activities Performed:
Executed network traffic interception scenarios.
Analyzed insecure service exposure.
Studied SMB relay and NTLM hash capture concepts.
Simulated Man-in-the-Middle attack logic.
Documented attack ID, technique used, and outcome.
Outcome:
Demonstrated understanding of protocol misconfigurations and traffic interception techniques.

5️⃣ Mobile Application Testing Lab
Objective:
Perform static and dynamic analysis on Android applications.
Activities Performed:
Conducted static analysis using MobSF.
Identified insecure storage vulnerabilities.
Studied runtime function manipulation concepts.
Logged vulnerability ID, severity, and target application.
Documented mobile security findings.
Outcome:
Successfully analyzed application security posture and documented risks with screenshots.

🛡 6️⃣ Capstone Project – Full VAPT Engagement
🎯 Objective
Conduct a complete penetration testing engagement on a HackTheBox virtual machine and produce structured documentation including exploitation, remediation, and reporting.
🔍 Step 1 – VPN Connection
Connected to HackTheBox network using OpenVPN.
Verified tunnel interface (tun0) from Kali Linux.
Confirmed assigned VPN IP address.

🔎 Step 2 – Reconnaissance
Performed full port scan using Nmap.
Identified open Telnet service on port 23.
Determined service version and OS details.

🧨 Step 3 – Exploitation
Used Metasploit auxiliary Telnet login module.
Successfully authenticated as root.
Verified system access using:
whoami
id
hostname
Accessed /root/flag.txt to confirm compromise.
Result:
Achieved full administrative (root) access.

🧪 Step 4 – Vulnerability Assessment (OpenVAS)
Started Greenbone GVM services.
Configured new scan target.
Executed full vulnerability scan.
Identified:
Insecure Telnet exposure
ICMP timestamp disclosure
TCP timestamp information leakage
Generated PDF report.
Documented severity classification and screenshots.

🌐 Step 5 – Web & API Testing (Burp Suite)
Configured browser proxy.
Attempted HTTP-based enumeration.
Verified absence of active web service.
Documented interception workflow and findings.

📊 Activity Log Format Used
Timestamp	            Target IP	    Vulnerability    	 PTES Phase
Logged during test	10.129.12.193	 Telnet Root Access	 Exploitation

🚨 Major Security Finding
The target machine allowed remote root login over Telnet without secure authentication controls.
This vulnerability enabled full system compromise and represented a critical security risk due to:
Plaintext credential transmission
No encryption
Direct administrative access
Lack of access restriction

🛠 Remediation Recommendations
Disable Telnet service immediately.
Replace Telnet with SSH.
Disable direct root remote login.
Apply system security updates.
Configure firewall rules.
Enforce least privilege principle.
Perform rescan using OpenVAS after remediation.

📄 Documentation Included in Week-4 Folder
📸 All tool screenshots
📄 OpenVAS scan report (PDF)
📄 Metasploit exploitation proof
📄 Burp Suite testing evidence
📄 300-word PTES report
📄 150-word stakeholder briefing
📄 Workflow steps documentation

🎯 Learning Outcome
Through this week’s execution, I strengthened my practical understanding of:
Exploitation workflows
Service misconfiguration risks
API testing methodology
Privilege escalation logic
Network protocol attack simulation
Professional VAPT reporting

This week simulated a real penetration testing engagement from reconnaissance to remediation documentation.
