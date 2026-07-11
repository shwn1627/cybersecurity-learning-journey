# 🔐 Cybersecurity Learning Journey

![Status](https://img.shields.io/badge/Status-Active-brightgreen)
![Tasks](https://img.shields.io/badge/Tasks_Completed-3-blue)
![Platform](https://img.shields.io/badge/Platform-Kali_Linux-557C94?logo=kalilinux&logoColor=white)
![Docker](https://img.shields.io/badge/Container-Docker-2496ED?logo=docker&logoColor=white)

Research • Security • Threat Intelligence • Ethical Hacking

This repository documents my progress in cybersecurity through research, practical tasks, security analysis, and hands-on projects. It's a portfolio of what I've built and learned so far — reconnaissance, vulnerability assessment, threat intelligence, and lab work — with each task written up the way a real security analyst would document it.

---

## 🎯 Objectives

- Build a strong foundation in cybersecurity concepts
- Understand modern cyber threats and attack vectors
- Develop practical security skills through hands-on projects
- Explore ethical hacking methodologies and defensive strategies
- Document what I learn as I go, and keep improving

---

## 📂 Repository Structure

```text
Cybersecurity-Learning-Journey/
│
├── task1/
│   └── Cybersecurity_Threat_Report_Task1_Shawn_Rodrigues.pdf
│
├── task2/
│   ├── Full_LAB_Build_Report_Shawn_Rodrigues_Task2.pdf
│   └── Evidence/
│
├── task3/
│   ├── README.md
│   ├── commands-used.txt
│   ├── findings-summary.md
│   ├── references.md
│   ├── Report/
│   │   └── Task3_Vulnerability_Assessment_Report_ShawnRodrigues.docx
│   └── Evidence/
│       ├── Nmap/
│       ├── Nikto/
│       ├── Dirsearch/
│       └── Screenshots/
│
└── README.md
```

---

## ✅ Completed Tasks

| # | Task | Focus | Status |
|---|---|---|---|
| 1 | [Threat Intelligence Report](./task1) | Cyber Threat Research | ✅ Done |
| 2 | [Cybersecurity Lab Setup](./task2) | Environment Build | ✅ Done |
| 3 | [Vulnerability Assessment](./task3) | OWASP Juice Shop | ✅ Done |

---

### Task 1 — Cybersecurity Threat Landscape (2024–2025)

A Threat Intelligence Report analyzing major cybersecurity threats affecting organizations and individuals.

**Topics Covered**
- AI-Powered Phishing Attacks
- Ransomware-as-a-Service (RaaS)
- Cloud Security Misconfigurations
- Internet of Things (IoT) Vulnerabilities
- Zero-Day Exploits

**Additional Areas**
- Impact Analysis
- Real-World Case Studies
- Preventive Measures
- Future Cybersecurity Trends
- Security Recommendations

---

### Task 2 — Cybersecurity Lab Setup

This project documents the creation of a personal cybersecurity lab using Oracle VirtualBox, Kali Linux, Docker, and OWASP Juice Shop — a safe, isolated environment for practicing network analysis, web application testing, vulnerability assessment, and traffic monitoring.

**Lab Components**

| Component | Details |
|---|---|
| Attacker Machine | Kali Linux 2026.1 |
| Vulnerable Target | OWASP Juice Shop |
| Networking | NAT Adapter, Host-Only Adapter |
| Security Tools | Nmap, Burp Suite Community Edition, Wireshark, Docker |

**Activities Performed**
- Kali Linux deployment
- Network configuration
- Docker installation
- OWASP Juice Shop deployment
- Ping validation
- Nmap host discovery
- HTTP traffic analysis using Burp Suite
- Packet capture using Wireshark

**Key Learning Outcomes**
- Virtualization fundamentals
- Network segmentation
- Docker container deployment
- Web application testing
- Network traffic analysis
- Security tool usage

All screenshots and evidence are in the Task-2 `Evidence/` folder.

---

### Task 3 — Vulnerability Assessment on OWASP Juice Shop

A black-box vulnerability assessment on OWASP Juice Shop, running in a Docker container on Kali Linux, using Nmap, Nikto, and Dirsearch.

**Lab Components**

| Component | Details |
|---|---|
| Attacker Machine | Kali Linux |
| Target | OWASP Juice Shop (Docker container) |
| Assessment Type | Black Box Vulnerability Assessment |
| Access URL | http://localhost:3000 |

**Tools Used**

| Tool | Purpose |
|---|---|
| Nmap | Network reconnaissance and service enumeration |
| Nikto | Web server vulnerability scanning |
| Dirsearch | Hidden directory and endpoint discovery |
| Docker | Containerized deployment |

**Activities Performed**
- Host discovery and network scanning
- Port and service enumeration with Nmap
- Web server misconfiguration scanning with Nikto
- Hidden directory/endpoint discovery with Dirsearch
- Risk analysis and severity rating of findings
- Professional report writing with remediation recommendations

**Key Findings Summary**

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

**Key Learning Outcomes**
- Network reconnaissance using Nmap
- Web server vulnerability analysis
- Directory enumeration techniques
- Security header analysis
- Risk assessment and severity rating
- Professional vulnerability assessment reporting

**Deliverables**
- Full Vulnerability Assessment Report (Word format, includes appendices)
- Commands used, findings summary, and references
- Complete evidence set (scan outputs + screenshots)

All screenshots and evidence are in the Task-3 `Evidence/` folder. See the [Task-3 README](./task3/README.md) for full details.

---

## 🛠 Skills & Domains

Cybersecurity Fundamentals · Threat Intelligence · Risk Assessment · Vulnerability Analysis · Ethical Hacking · Network Security · Cloud Security · Incident Analysis

**Tools:** Kali Linux, Docker, Nmap, Wireshark, Burp Suite, Nikto, Dirsearch

---

## 📚 Learning Resources

- NIST Cybersecurity Framework
- OWASP Security Guidelines
- CISA Security Advisories
- IBM Security Research
- ENISA Threat Landscape Reports
- Industry Threat Intelligence Reports

---

## 🚀 Future Goals

- Perform advanced vulnerability assessments
- Learn web application security testing in more depth
- Explore penetration testing methodologies
- Develop security automation skills
- Build more hands-on cybersecurity projects
- Work toward industry-recognized certifications

---

## ⭐ Note

This repository is a living portfolio and will keep growing as I complete new cybersecurity projects and learning activities. If you found it useful, a star is always appreciated.
