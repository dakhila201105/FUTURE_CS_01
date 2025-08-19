# FUTURE_CS_01
# 🐝 bWAPP Security Testing Internship task 01

This repository documents my work on the **bWAPP (Buggy Web Application)** security testing internship project.  
The goal of this task was to explore common web application vulnerabilities, simulate attacks, and create a structured **security report** following the **OWASP Top 10** guidelines.

---

## 📌 About bWAPP
bWAPP (Buggy Web Application) is a deliberately insecure web application designed for security testing and ethical hacking practice.  
It contains a wide range of vulnerabilities, including SQL Injection, Cross-Site Scripting (XSS), CSRF, Broken Authentication, and many others.

---

## 🎯 Internship Task
- Set up and run bWAPP locally on my system.  
- Explore and test different vulnerabilities.  
- Document **3–5 real vulnerabilities** with:
  - Attack steps
  - Screenshots
  - OWASP Top 10 mapping
  - Mitigation steps  
- Generate a polished **PDF Security Report** as the final deliverable.

---

## 🔍 Vulnerabilities Tested
I focused on the following key vulnerabilities:

1. **SQL Injection (Union-Based)**  
   - Exploited via input fields to extract database information.  
   - **OWASP Mapping:** Injection (A03:2021).  

2. **SQL Injection (Blind – Boolean/Time-Based)**  
   - Demonstrated data extraction even when errors are hidden.  
   - **OWASP Mapping:** Injection (A03:2021).  

3. **Cross-Site Scripting (XSS)**  
   - Injected malicious JavaScript into input fields.  
   - **OWASP Mapping:** Cross-Site Scripting (A07:2021).  

4. **Cross-Site Request Forgery (CSRF)**  
   - Forged unauthorized actions using crafted requests.  
   - **OWASP Mapping:** CSRF (part of A05:2021 – Security Misconfiguration).  

---

##  Deliverables
- **Security Report (PDF):** Contains detailed documentation with screenshots, risk ratings, and mitigation steps.  
- **Tool Logs:** Burp Suite / OWASP ZAP logs of exploit attempts.  

---

##  Key Learnings
- Practical hands-on experience with **realistic web vulnerabilities**.  
- How to map vulnerabilities to **OWASP Top 10**.  
- Writing a **professional security report** with mitigations.  
- Importance of secure coding practices to prevent common attacks.  

---



**Author:** Akhila D  
**Email:** akhila8812@gmail.com  
