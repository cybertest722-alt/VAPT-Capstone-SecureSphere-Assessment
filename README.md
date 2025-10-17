# VAPT Capstone Project — SecureSphere Inc. Assessment

**Cyber Security Project | October 2025**

---

## Project Overview
This project is part of my Cyber Security Capstone, focusing on **Vulnerability Assessment and Penetration Testing (VAPT)** of both a web application and a deliberately vulnerable virtual machine (Metasploitable3).  
The goal was to simulate real-world attack scenarios, identify vulnerabilities, and recommend remediation measures.

---

## Objectives
- Identify security weaknesses in the web and system environments.
- Perform vulnerability scanning, exploitation, and reporting using industry-standard tools.
- Demonstrate risk impact and provide mitigation recommendations.

---

## Target Environment
| Target | Description | IP Address |
|---------|--------------|------------|
| Target 1 | Web Application (ctflearn.com) | 104.21.14.37 |
| Target 2 | Metasploitable3 VM | 10.244.168.40 |

**Attacker Machine:** Kali Linux  
**Tester:** Ilo Paul Okechukwu  

---

## Tools & Frameworks Used
|      Phase     |            Tools            |                Purpose                    |
|----------------|-----------------------------|-------------------------------------------|
| Reconnaissance | whois, nslookup, nmap | Information gathering & service discovery |
| Scanning       | Nessus, Nikto            | Web vulnerability assessment |
| Web Testing | SQLmap, Dirb | SQLi testing and directory discovery and enumeration|
| Exploitation   | Metasploit (msfconsole)   | System penetration and exploitation     |
| Reporting      | Markdown, MS Word           | Documentation and presentation            |

---

## Techniques Applied
- Port and Service Enumeration  
- Web Server Scanning  
- Directory Enumeration  
- SQL Injection Testing  
- Exploitation and Post-Exploitation (Metasploit)  
- Risk Evaluation and Reporting  

---

## Summary of Findings
|   Vulnerability        |         Severity        |        Impact        |               Recommendation               |
|------------------------|-------------------------|----------------------|--------------------------------------------|
| SQL Injection          | Critical                | Database compromise  | Sanitize inputs; use parameterized queries |
| Weak Password Policy   | High                    | Unauthorized access  | Enforce complex passwords & MFA            |
| Outdated Software      | Medium                  | Exploitable flaws    | Regular patching and updates               |
| Misconfigured Firewall | Medium                  | Exposure of services | Limit open ports & harden network          |

---

## Key Results
- Multiple open ports discovered (80, 443).  
- SQLi vulnerability confirmed through automated and manual testing.  
- Gained limited shell access on Metasploitable3 through Metasploit.  
- Recommendations provided for patching, input validation, and system hardening.

---

## Recommendations  
- Implement **strong password policies** and **multi-factor authentication (MFA)**.  
- Conduct **regular vulnerability scans** and **patch updates**.  
- Deploy **Web Application Firewalls (WAF)** and **Intrusion Detection Systems (IDS)**.  
- Enforce **input validation and sanitization** to prevent SQLi and XSS.  
- Limit access to **unnecessary services, directories, and ports**.  
- Provide **security awareness training** for staff.  

---

## Conclusion  
The assessment revealed multiple high and critical vulnerabilities in both web and system environments. Addressing these weaknesses through proper configuration, patching, and security controls will **significantly enhance the target’s security posture** and reduce exposure to cyber threats.
This project demonstrates practical application of VAPT methodologies, aligning with real-world penetration testing practices.  

---

## Repository Contents
- `/README.md` - Full project report 
- `/screenshots` - Visual evidence of tests and results  

---

## Disclaimer
This repository is for **educational and portfolio purposes only**.  
Do **not** use these techniques on unauthorized systems.  

---

## Author
**Ilo Paul Okechukwu**  
🌐 [LinkedIn](www.linkedin.com/in/paul-okechukwu-ilo-957992386)  
