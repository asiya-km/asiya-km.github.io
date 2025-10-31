---
layout: single
title: "Lab Challenges"
permalink: /lab-challenges/
---

## 1. Networking PCAP — Traffic Analysis
**Problem Statement:** Analyze DNS and HTTP traffic in a PCAP file to understand network communication patterns.  

**Approach:**  
- Open `http.cap` in Wireshark; use filters `dns` and `http`.  
- Reconstruct HTTP requests and responses, trace DNS queries to IP resolution.  

**Tools:** Wireshark, tshark  

**Screenshots:**  
- `assets/images/labs/http-dns.png`  
- `assets/images/labs/http-get.png`  

**Key Lessons:**  
Learned to trace network layers, interpret packet headers, and reconstruct HTTP flows for practical traffic analysis.

---

## 2. OWASP Juice Shop — Web Vulnerability Assessment
**Problem Statement:** Identify common web vulnerabilities in Juice Shop aligned to OWASP Top 10.  

**Approach:**  
- Selected 3 vulnerabilities: SQL Injection, XSS, Broken Authentication.  
- Tested manually and via Burp Suite; validated results in a controlled lab environment.  

**Tools:** Browser, Burp Suite  

**Screenshots:**  
- `assets/images/labs/juice-sqli.png`  
- `assets/images/labs/juice-xss.png`  
- `assets/images/labs/juice-auth.png`  

**Key Lessons:**  
Gained practical insight into web security risks, learned mitigation strategies, and documented reproducible testing steps.

---

## 3. TryHackMe — Offensive Security Labs
**Problem Statement:** Complete structured offensive security exercises including enumeration, exploitation, and privilege escalation.  

**Approach:**  
- Enumerated services using Nmap and Gobuster.  
- Exploited vulnerable services in isolated lab environments.  
- Escalated privileges and documented findings.  

**Tools:** Nmap, Gobuster, linPEAS, netcat, terminal   

**Key Lessons:**  
Learned systematic penetration testing workflows, evidence documentation, and practical mitigation recommendations.
