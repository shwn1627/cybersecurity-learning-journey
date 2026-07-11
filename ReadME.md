<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,20:0f2027,45:16222a,70:1b3a4b,100:2c5364&height=280&section=header&text=root@shawn:~%23&fontSize=62&fontColor=00ff9d&fontAlign=50&fontAlignY=34&animation=twinkling&desc=Cybersecurity%20Learning%20Journey%20%E2%80%94%20Recon.%20Scan.%20Report.&descAlignY=54&descSize=19&descColor=7ee8fa&descAlign=50" width="100%"/>

<sub>Kali Linux · Docker · Nmap · Nikto · Dirsearch · Threat Intelligence</sub>

</div>

```bash
┌──(shawn㉿kali)-[~]
└─$ whoami
> Cybersecurity learner | Ethical Hacker in training | Building in public

┌──(shawn㉿kali)-[~]
└─$ cat mission.txt
> Documenting my path through cybersecurity, one task, one scan,
> one report at a time — the same workflow real security analysts follow.
```

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=2800&pause=1200&color=00FF9D&center=true&vCenter=true&width=600&lines=nmap+-sV+-Pn+target;Scanning+for+vulnerabilities...;Documenting+findings...;Building+my+security+portfolio." alt="Typing SVG" />

<br/>

![Status](https://img.shields.io/badge/STATUS-ACTIVE-00ff9d?style=for-the-badge&labelColor=0d1117)
![Tasks](https://img.shields.io/badge/TASKS-3_COMPLETED-00d4ff?style=for-the-badge&labelColor=0d1117)
![Platform](https://img.shields.io/badge/OS-KALI_LINUX-557C94?style=for-the-badge&logo=kalilinux&logoColor=white&labelColor=0d1117)
![Docker](https://img.shields.io/badge/CONTAINER-DOCKER-2496ED?style=for-the-badge&logo=docker&logoColor=white&labelColor=0d1117)

---

## `> cat about.md`

This repository documents my progress in cybersecurity through research, practical tasks, security analysis, and hands-on lab work. It's a running log of what I've built and learned — reconnaissance, vulnerability assessment, threat intelligence, lab environments — each one written up the way a real analyst would document an engagement.

> **Note:** No exploitation is performed in any task. Everything here is reconnaissance, scanning, analysis, and reporting inside isolated lab environments only.

---

## `> cat objectives.txt`

```diff
+ Build a strong foundation in cybersecurity concepts
+ Understand modern cyber threats and attack vectors
+ Develop practical security skills through hands-on projects
+ Explore ethical hacking methodologies and defensive strategies
+ Document everything, and keep improving with every task
```

---

## `> tree .`

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

## `> ls -la tasks/`

<div align="center">

| # | Task | Focus | Status |
|:---:|---|---|:---:|
| 01 | [Threat Intelligence Report](./task1) | Cyber Threat Research | `DONE` |
| 02 | [Cybersecurity Lab Setup](./task2) | Environment Build | `DONE` |
| 03 | [Vulnerability Assessment](./task3) | OWASP Juice Shop | `DONE` |

</div>

---

<br/>

## `[ TASK_01 ]` Cybersecurity Threat Landscape (2024–2025)

```yaml
type: Threat Intelligence Report
target: Global threat landscape
output: Cybersecurity_Threat_Report_Task1_Shawn_Rodrigues.pdf
```

**Topics Covered**
- AI-Powered Phishing Attacks
- Ransomware-as-a-Service (RaaS)
- Cloud Security Misconfigurations
- Internet of Things (IoT) Vulnerabilities
- Zero-Day Exploits

**Additional Areas**
- Impact analysis and real-world case studies
- Preventive measures and security recommendations
- Future cybersecurity trends

<br/>

## `[ TASK_02 ]` Cybersecurity Lab Setup

```yaml
type: Environment Build
stack: VirtualBox + Kali Linux + Docker + OWASP Juice Shop
status: Fully operational
```

A personal, isolated cybersecurity lab — the foundation every later task runs on top of.

**Lab Components**

| Component | Details |
|---|---|
| Attacker Machine | Kali Linux 2026.1 |
| Vulnerable Target | OWASP Juice Shop |
| Networking | NAT Adapter, Host-Only Adapter |
| Security Tools | Nmap, Burp Suite CE, Wireshark, Docker |

**Activities Performed**
```bash
$ Kali Linux deployment
$ Network configuration (NAT + Host-Only)
$ Docker installation & container deployment
$ ping -c 4 <target>          # connectivity validation
$ nmap -sn <subnet>            # host discovery
$ burpsuite                    # HTTP traffic analysis
$ wireshark                    # packet capture
```

**Key Learning Outcomes**
Virtualization fundamentals · Network segmentation · Docker deployment · Web app testing · Traffic analysis · Security tool usage

📁 Evidence & screenshots → [`task2/Evidence/`](./task2)

<br/>

## `[ TASK_03 ]` Vulnerability Assessment — OWASP Juice Shop

```yaml
type: Black Box Vulnerability Assessment
target: OWASP Juice Shop (Docker container)
url: http://localhost:3000
tools: [Nmap, Nikto, Dirsearch]
```

**Assessment Flow**

```text
Recon → Port Scan (Nmap) → Web Scan (Nikto) → Dir Enum (Dirsearch) → Risk Analysis → Report
```

**Findings**

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

**Deliverables**
- Full Vulnerability Assessment Report (Word format, with appendices)
- Commands used, findings summary, references
- Complete evidence set — scan outputs + screenshots

📄 Full write-up → [`task3/README.md`](./task3/README.md)

---

## `> cat skills.json`

```json
{
  "core_skills": [
    "Cybersecurity Fundamentals", "Threat Intelligence", "Risk Assessment",
    "Vulnerability Analysis", "Ethical Hacking", "Network Security",
    "Cloud Security", "Incident Analysis"
  ],
  "tools": ["Kali Linux", "Docker", "Nmap", "Wireshark", "Burp Suite", "Nikto", "Dirsearch"]
}
```

---

## `> cat references.txt`

```text
[1] NIST Cybersecurity Framework
[2] OWASP Security Guidelines
[3] CISA Security Advisories
[4] IBM Security Research
[5] ENISA Threat Landscape Reports
[6] Industry Threat Intelligence Reports
```

---

## `> cat roadmap.todo`

```diff
- Perform advanced vulnerability assessments
- Learn web application security testing in more depth
- Explore penetration testing methodologies
- Develop security automation skills
- Build more hands-on cybersecurity projects
- Earn industry-recognized certifications
```

---

<div align="center">

```bash
┌──(shawn㉿kali)-[~]
└─$ echo "thanks for reading — this repo keeps growing 🌱"
```

**⭐ If this was useful, a star helps a lot.**

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:203a43,50:0f2027,100:0d1117&height=120&section=footer" width="100%"/>

</div>
