# OWASP Juice Shop – Penetration Testing Report (with Risk Ratings)  

[owasp_juice_shop_pentest.docx](https://github.com/piyush110022/Web-Application-Pen-Testing-OWASP-/blob/main/owasp_juice_shop_pentest.docx)

## 📌 Project Overview  
This repository showcases a **penetration testing project** conducted on **OWASP Juice Shop**, a deliberately vulnerable web application.  
The project demonstrates **end-to-end penetration testing methodology** — from reconnaissance to exploitation — and presents findings in a **consulting-style report** with risk ratings and remediation steps.  

---

## 🎯 Objectives  
- Apply a structured penetration testing approach.  
- Identify and exploit common web application vulnerabilities.  
- Provide risk ratings (Critical, High) for each issue.  
- Deliver a professional pentest report for recruiters and hiring managers.  

---

## 🛠️ Tools & Techniques Used  
- **Reconnaissance**: Nmap, Gobuster, Subdomain Enumeration  
- **Exploitation**: Burp Suite, Manual Testing  
- **Documentation**: Screenshots, PoC Payloads, PDF Report  
- **Vulnerabilities Tested**: SQL Injection, IDOR, XSS, Broken Authentication  

---

## 🔑 Key Findings  
- **SQL Injection – Login Bypass [Critical]**  
- **Broken Authentication [Critical]**  
- **Insecure Direct Object Reference (IDOR) [High]**  
- **Cross-Site Scripting (XSS) [High]**  

---

## 📊 Risk Rating Summary  

| Vulnerability                           | Severity    | Impact |
|-----------------------------------------|-------------|--------|
| SQL Injection – Login Bypass            | 🔴 Critical | Full authentication bypass, admin access |
| Broken Authentication                   | 🔴 Critical | Unauthorized access with weak credentials |
| Insecure Direct Object Reference (IDOR) | 🟠 High     | Unauthorized access to other users' data |
| Cross-Site Scripting (XSS)              | 🟠 High     | Session hijacking, account takeover |

---

## ⚠️ Disclaimer  
This assessment was conducted in a **controlled lab environment** using OWASP Juice Shop, a vulnerable application designed for training.  
The work is for **educational and portfolio purposes only**.  

---

 
