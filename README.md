# 🏴 TryHackMe - Silver Platter 🏴

## 🔍 Overview

This repository contains a penetration testing report for the **TryHackMe - Silver Platter** challenge. The assessment includes reconnaissance, enumeration, exploitation, and privilege escalation techniques to gain root access to the target system.

## 🛠️ Steps Covered

- **Enumeration**  
  - **Nmap** scan to identify open ports and running services.  
  - Discovery of **two HTTP services** on ports **80** and **8080**.  
  - Content discovery using **Gobuster** to find hidden directories.  

- **Exploitation**  
  - Identified a vulnerable application: **Silverpeas**.  
  - Exploited a misconfigured authentication mechanism using **BurpSuite**.  
  - Gained access to the admin panel and extracted sensitive information.  

- **Privilege Escalation**  
  - Discovered credentials by analyzing system logs.  
  - Escalated privileges from **user (tim) → root** using password leakage.  
  - Successfully captured both **user** and **root flags**.  

## 📄 Report

For a detailed step-by-step breakdown, refer to the **full report** included in this repository:  
📄 [`tryHackMe_Task.pdf`](./tryHackMe_Task.pdf)


## 🚀 Conclusion

This challenge demonstrated practical **CTF techniques**, including service enumeration, web application exploitation, and Linux privilege escalation.  

🔒 *Ethical hacking is a learning process—always practice responsibly!* 😈  

---

