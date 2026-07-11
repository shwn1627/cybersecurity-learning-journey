<div align="center">

# 🔐 Cybersecurity Learning Journey

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&size=22&pause=1000&color=00F7FF&center=true&vCenter=true&width=600&lines=Research+%E2%80%A2+Security+%E2%80%A2+Threat+Intelligence;Ethical+Hacking+%E2%80%A2+Vulnerability+Assessment;Building+a+Cybersecurity+Portfolio+One+Task+at+a+Time" alt="Typing SVG" />

<br/>

![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=for-the-badge)
![Tasks](https://img.shields.io/badge/Tasks_Completed-3-blue?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Kali_Linux-557C94?style=for-the-badge&logo=kalilinux&logoColor=white)
![Docker](https://img.shields.io/badge/Container-Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-green?style=for-the-badge)

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0F2027,50:203A43,100:2C5364&height=160&section=header&text=Welcome%20to%20my%20Security%20Portfolio&fontSize=28&fontColor=ffffff&animation=fadeIn" width="100%" />

</div>

---

## 👋 About This Repository

This repository documents my journey through **cybersecurity, ethical hacking, and threat intelligence** — one hands-on task at a time.

Each project here is built to reflect real-world security workflows: reconnaissance, scanning, analysis, documentation, and reporting — the same process followed by professional security analysts.

> 💡 Every task includes its own detailed report, evidence, and a dedicated README.

---

## 🎯 Objectives

<table>
<tr>
<td width="50%" valign="top">

- 🧱 Build a strong foundation in cybersecurity concepts
- 🌐 Understand modern cyber threats and attack vectors
- 🛠️ Develop practical security skills through projects
- 🕵️ Explore ethical hacking methodologies

</td>
<td width="50%" valign="top">

- 🛡️ Practice defensive & offensive security strategies
- 📄 Produce professional, portfolio-ready documentation
- 📈 Track continuous learning and improvement
- 🎓 Work toward industry certifications

</td>
</tr>
</table>

---

## 📂 Repository Structure

```text
Cybersecurity-Learning-Journey/
│
├── Task-1-Threat-Intelligence-Report/
│   └── Cybersecurity_Threat_Report_Task1_Shawn_Rodrigues.pdf
│
├── Task-2-Cybersecurity-Lab-Setup/
│   ├── Full_LAB_Build_Report_Shawn_Rodrigues_Task2.pdf
│   └── Evidence/
│
├── Task-3-Vulnerability-Assessment/
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

<div align="center">

| # | Task | Focus | Status |
|---|---|---|---|
| 1 | [Threat Intelligence Report](./Task-1-Threat-Intelligence-Report) | Cyber Threat Research | ✅ Done |
| 2 | [Cybersecurity Lab Setup](./Task-2-Cybersecurity-Lab-Setup) | Environment Build | ✅ Done |
| 3 | [Vulnerability Assessment](./Task-3-Vulnerability-Assessment) | OWASP Juice Shop | ✅ Done |

</div>

---

<details open>
<summary><h3>📊 Task 1 — Cybersecurity Threat Landscape (2024–2025)</h3></summary>

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

</details>

---

<details open>
<summary><h3>🖥️ Task 2 — Cybersecurity Lab Setup</h3></summary>

This project documents the successful creation of a personal cybersecurity laboratory environment using Oracle VirtualBox, Kali Linux, Docker, and OWASP Juice Shop.

The lab was designed to provide a safe and isolated environment for practicing cybersecurity concepts such as network analysis, web application testing, vulnerability assessment, and traffic monitoring.

**Lab Components**

| Component | Details |
|---|---|
| Attacker Machine | Kali Linux 2026.1 |
| Vulnerable Target | OWASP Juice Shop |
| Networking | NAT Adapter, Host-Only Adapter |
| Security Tools | Nmap, Burp Suite Community Edition, Wireshark, Docker |

**Activities Performed**
- Kali Linux Deployment
- Network Configuration
- Docker Installation
- OWASP Juice Shop Deployment
- Ping Validation
- Nmap Host Discovery
- HTTP Traffic Analysis using Burp Suite
- Packet Capture using Wireshark

**Key Learning Outcomes**
- Virtualization Fundamentals
- Network Segmentation
- Docker Container Deployment
- Web Application Testing
- Network Traffic Analysis
- Security Tool Usage

All screenshots and evidence are available in the Task-2 `Evidence/` folder.

</details>

---

<details open>
<summary><h3>🔓 Task 3 — Vulnerability Assessment on OWASP Juice Shop</h3></summary>

A black-box vulnerability assessment performed on OWASP Juice Shop, running inside a Docker container on Kali Linux, using Nmap, Nikto, and Dirsearch.

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
- Commands Used, Findings Summary, and References
- Complete evidence set (scan outputs + screenshots)

All screenshots and evidence are available in the Task-3 `Evidence/` folder.

👉 See the [Task-3 README](./Task-3-Vulnerability-Assessment/README.md) for full details.

</details>

---

## 🛠 Skills & Domains

<div align="center">

![Cybersecurity](https://img.shields.io/badge/-Cybersecurity_Fundamentals-0A1128?style=flat-square)
![Threat Intel](https://img.shields.io/badge/-Threat_Intelligence-0A1128?style=flat-square)
![Risk](https://img.shields.io/badge/-Risk_Assessment-0A1128?style=flat-square)
![Vuln](https://img.shields.io/badge/-Vulnerability_Analysis-0A1128?style=flat-square)
![Ethical Hacking](https://img.shields.io/badge/-Ethical_Hacking-0A1128?style=flat-square)
![Network](https://img.shields.io/badge/-Network_Security-0A1128?style=flat-square)
![Cloud](https://img.shields.io/badge/-Cloud_Security-0A1128?style=flat-square)
![Incident](https://img.shields.io/badge/-Incident_Analysis-0A1128?style=flat-square)

</div>

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

- [ ] Perform advanced Vulnerability Assessments
- [ ] Learn Web Application Security Testing
- [ ] Explore Penetration Testing Methodologies
- [ ] Develop Security Automation Skills
- [ ] Build Hands-on Cybersecurity Projects
- [ ] Earn Industry-Recognized Certifications

---

<div align="center">

## ⭐ Note

This repository is a living portfolio and will continue to grow as I complete new cybersecurity projects, research activities, and practical learning experiences.

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:2C5364,50:203A43,100:0F2027&height=100&section=footer" width="100%" />

**If you found this useful, consider ⭐ starring the repo!**

</div>
