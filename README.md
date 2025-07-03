#  Web Application Security Projects: SQL Injection & XSS

This repository contains practical demonstrations of two critical web application vulnerabilities:  
**SQL Injection (SQLi)** and **Cross-Site Scripting (XSS)**.

These projects showcase how attackers can exploit insecure coding practices and how developers can prevent such issues.

---

##  Projects Overview

### 1.  SQL Injection – Login Bypass

####  Description:
This project demonstrates how attackers can manipulate SQL queries in a vulnerable login form to gain unauthorized access—typically as an administrator.

####  Objectives:
- Understand the mechanics of SQL Injection
- Bypass authentication without valid credentials
- Identify insecure query handling
- Explore mitigation strategies (e.g., prepared statements)

####  Tools & Stack:
- Python/PHP backend (or simulated app like DVWA, bWAPP, or PortSwigger Lab)
- SQL database (e.g., MySQL)
- Burp Suite (for intercepting HTTP requests)
- Web browser

####  Example Payload:
```sql
' OR '1'='1 --
