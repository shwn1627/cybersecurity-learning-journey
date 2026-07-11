# 🛡️ Task 3 - Vulnerability Assessment using OWASP Juice Shop

![Status](https://img.shields.io/badge/Status-Completed-brightgreen)
![Platform](https://img.shields.io/badge/Platform-Kali_Linux-blue)
![Docker](https://img.shields.io/badge/Container-Docker-2496ED)
![Target](https://img.shields.io/badge/Target-OWASP_Juice_Shop-red)
![Tools](https://img.shields.io/badge/Tools-Nmap%20%7C%20Nikto%20%7C%20Dirsearch-orange)
![License](https://img.shields.io/badge/License-MIT-green)

---

## 📌 Overview

This project documents the third task of my Cybersecurity Learning Journey, where I performed a **Vulnerability Assessment** on the intentionally vulnerable **OWASP Juice Shop** application running inside a Docker container on Kali Linux.

The assessment focused on identifying exposed network services, web server misconfigurations, hidden directories, and publicly accessible resources without exploiting the application.

---

## 🎯 Objectives

- Perform host and service enumeration
- Identify exposed services
- Detect common web server misconfigurations
- Discover hidden files and directories
- Document findings professionally
- Recommend security improvements

---

## 🖥️ Lab Environment

| Component | Details |
|---|---|
| Operating System | Kali Linux |
| Container Platform | Docker |
| Target | OWASP Juice Shop |
| Assessment Type | Black Box Vulnerability Assessment |

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| Nmap | Network reconnaissance and service enumeration |
| Nikto | Web server vulnerability scanning |
| Dirsearch | Hidden directory discovery |
| Docker | Containerized deployment |
| Firefox | Manual verification |

---

## 📂 Project Structure

```
Task-3-Vulnerability-Assessment/
│
├── README.md
├── commands-used.txt
├── findings-summary.md
├── references.md
│
├── Report/
│   └── Vulnerability_Assessment_Report.pdf
│
└── Evidence/
    ├── Nmap/
    ├── Nikto/
    ├── Dirsearch/
    └── Screenshots/
```

---

## 🔬 Assessment Workflow

```
Start Juice Shop
      │
      ▼
Network Discovery
      │
      ▼
Service Enumeration (Nmap)
      │
      ▼
Web Server Scan (Nikto)
      │
      ▼
Directory Enumeration (Dirsearch)
      │
      ▼
Analysis
      │
      ▼
Documentation
```

---

## 📊 Findings Summary

| Finding | Severity |
|---|---|
| Open Port 3000 | Medium |
| Missing Content Security Policy | Medium |
| Missing HSTS Header | Medium |
| Missing Referrer Policy | Low |
| Missing Permissions Policy | Low |
| robots.txt Accessible | Low |
| API Documentation Exposed | Medium |
| Swagger Interface Accessible | Medium |

For complete findings, refer to **findings-summary.md**.

---

## 📸 Evidence

The `Evidence/` folder contains:

- Nmap scan results
- Nikto scan results
- Dirsearch results
- Assessment screenshots

---

## 📄 Documentation

This project includes:

- Vulnerability Assessment Report
- Commands Used
- Findings Summary
- References

---

## 📚 Learning Outcomes

Through this assessment I learned:

- Network reconnaissance using Nmap
- Web server vulnerability analysis
- Directory enumeration
- Security header analysis
- Vulnerability documentation
- Risk assessment
- Professional reporting

---

## ⚠️ Disclaimer

OWASP Juice Shop is an intentionally vulnerable application designed for educational purposes.

All testing performed in this repository was conducted in a controlled laboratory environment.

---

## 🚀 Author

**Shawn Rodrigues**

Computer Science Engineering Student
Cybersecurity Enthusiast
