<div align="center">

<img src="https://readme-typing-svg.demolab.com/?font=Fira+Code&size=22&pause=1000&color=00FF9C&center=true&vCenter=true&width=600&lines=Aspiring+Penetration+Tester;Security+Researcher;Breaking+systems+to+build+better+defenses" alt="Typing SVG" />

# 👋 Hi, I'm Toxkay

**Penetration Tester in training · Security Researcher · BSc Computers & AI @ Cairo University (2027)**

[![Website](https://img.shields.io/badge/Website-toxkay.github.io-000000?style=for-the-badge&logo=githubpages&logoColor=white)](https://toxkay.github.io)
[![GitHub followers](https://img.shields.io/github/followers/Toxkay?style=for-the-badge&logo=github&label=Follow&color=181717)](https://github.com/Toxkay)
[![Profile Views](https://komarev.com/ghpvc/?username=Toxkay&style=for-the-badge&color=blueviolet)](https://github.com/Toxkay)

</div>

<br/>

> [!IMPORTANT]
> **Highlights**
> - 🛠️ Built **ReconW** — a local-first, 5-stage recon automation pipeline for bug bounty & attack-surface work
> - 🌐 Designed and secured a simulated enterprise network (ZPF, ACLs, AAA, VPN, VLANs) in Cisco Packet Tracer
> - 🎓 BSc in Computers & AI @ Cairo University, Class of 2027
> - 🔍 Writeups, notes, and deep project breakdowns live on **[toxkay.github.io](https://toxkay.github.io)**

<br/>

## 📌 Table of Contents
- [About Me](#-about-me)
- [Security Focus](#-security-focus)
- [Highlighted Security Projects](#-highlighted-security-projects)
- [Tech Stack](#-tech-stack)
- [Other Projects](#-other-projects)
- [GitHub Stats](#-github-stats)
- [Currently Learning](#-currently-learning)
- [Contributing](#-contributing)
- [License](#-license)
- [Contact](#-contact)

---

## 🧭 About Me

I'm an aspiring penetration tester and security researcher pursuing a **BSc in Computers & AI at Cairo University**. My focus is offensive security tooling and practical network defense — automating reconnaissance pipelines for bug bounty work on one side, and designing/hardening simulated enterprise networks on the other.

I like projects that ship a working artifact, not just theory — something you can actually run, break, and improve.

`[Add your bio here — 1–2 more sentences on your background, interests, or career goals]`

---

## 🛡️ Security Focus

> [!TIP]
> **Where I spend most of my time**
> - Reconnaissance & attack-surface mapping automation
> - Network security engineering — segmentation, firewalling, access control
> - Explainable, auditable tooling over black-box scripts
> - Hands-on validation — every project ships with something runnable, not just a writeup

---

## ⭐ Highlighted Security Projects

### 🔎 [ReconW — Security Reconnaissance Pipeline Orchestrator](https://github.com/Toxkay/reconw-orchestrator)

**A local-first, 5-stage recon automation pipeline that turns manual bug bounty recon into a repeatable, auditable process.**

**Why it matters:** Early-stage recon is usually a pile of disconnected CLI tools and manual note-taking. ReconW chains industry-standard tools into one pipeline, enforces strict in-scope/out-of-scope boundaries, and logs every command and finding for provenance — so results are reproducible and defensible, not just "trust me."

**Key features:**
- 🔗 **5-stage pipeline:** Subfinder → DNSx → HTTPx → Katana → explainable Python scoring engine
- 🗂️ **Program-centric SQLite storage** — dedicated, queryable database per target program (e.g. `tiktok.db`)
- 📊 **Explainable prioritization** — transparent scoring rules (e.g. `+30 Admin/Auth`, `+20 Sensitive APIs`) rank findings from Critical → Info
- 🖥️ **Offline interactive HTML dashboard** — client-side search, severity filtering, and JSON export, no server required
- 🧩 **Cross-platform** — Linux (Kali/Ubuntu/Debian), macOS, and Windows

`[Insert architecture diagram here — e.g. Subfinder → DNSx → HTTPx → Katana → Prioritization Engine → HTML Report]`

**Quick start:**
```bash
git clone https://github.com/Toxkay/reconw-orchestrator.git
cd reconw-orchestrator
pip install -e .

reconw doctor                                          # verify dependencies
reconw run -p "ProgramName" -i inscope.txt -o outscope.txt
```

<br/>

### 🌐 [Summer-Intern-FInal-Project-NETSEC — Enterprise Network Security Lab](https://github.com/Toxkay/Summer-Intern-FInal-Project-NETSEC)

**A Cisco Packet Tracer lab implementing a layered, segmented enterprise network security design.**

**Why it matters:** Network security theory means little without hands-on config experience. This lab demonstrates real-world defensive architecture — from perimeter firewalling down to role-based admin access — validated inside a working simulated topology rather than described in slides.

**Key features:**
- 🧱 **Zone-Based Policy Firewall (ZPF)** — segments the network and enforces inter-zone policy
- 🚧 **Standard & Extended ACLs** — controls traffic flow and restricts unauthorized access
- 🔐 **AAA (Authentication, Authorization, Accounting)** — manages admin access and tracks configuration changes
- 🔒 **VPN** — secure remote access and site-to-site connectivity
- 🧩 **VLAN segmentation** — isolates traffic across the topology for security and performance
- 👤 **CLI Views** — role-based access for network administrators

**Quick start:**
```bash
git clone https://github.com/Toxkay/Summer-Intern-FInal-Project-NETSEC.git
# Open the .pkt file in Cisco Packet Tracer to explore the topology,
# then inspect each device's CLI for ZPF rules, ACLs, AAA, VPN, and VLAN config.
```

---

## 🧰 Tech Stack

<div align="center">

**Offensive Security & Testing**

![Burp Suite](https://img.shields.io/badge/Burp_Suite-FF6633?style=for-the-badge&logo=burp-suite&logoColor=white)
![Kali Linux](https://img.shields.io/badge/Kali_Linux-557C94?style=for-the-badge&logo=kali-linux&logoColor=white)
![Wireshark](https://img.shields.io/badge/Wireshark-1679A7?style=for-the-badge&logo=wireshark&logoColor=white)
![Nmap](https://img.shields.io/badge/Nmap-0078D4?style=for-the-badge&logo=nmap&logoColor=white)
![OWASP ZAP](https://img.shields.io/badge/OWASP_ZAP-00549E?style=for-the-badge&logo=owasp&logoColor=white)
![Metasploit](https://img.shields.io/badge/Metasploit-2596CD?style=for-the-badge&logo=metasploit&logoColor=white)

**Languages & Scripting**

![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=c%2B%2B&logoColor=white)
![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-003B57?style=for-the-badge&logo=sqlite&logoColor=white)
![Bash](https://img.shields.io/badge/Bash-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white)

**Networking & Infrastructure**

![Cisco](https://img.shields.io/badge/Cisco-1BA0D7?style=for-the-badge&logo=cisco&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

</div>

> ReconW also orchestrates Go-based reconnaissance tooling from [ProjectDiscovery](https://github.com/projectdiscovery) (Subfinder, DNSx, HTTPx, Katana) as external dependencies.

---

## 📂 Other Projects

| Project | Focus Area | Description |
| :--- | :--- | :--- |
| [Vole-Machine](https://github.com/Toxkay/Vole-Machine) | Systems Programming | Custom virtual machine in C++ — ISA design, CPU simulation, memory management |
| [CS341-A3-CPU-Scheduler](https://github.com/Toxkay/CS341-A3-CPU-Scheduler) | Systems Programming | CPU scheduling simulator implementing FCFS, SJF, Round Robin, and Priority scheduling |
| [CS341-A1-Command-Line-Interpreter](https://github.com/Toxkay/CS341-A1-Command-Line-Interpreter) | Systems Programming | Unix-like shell — parsing, process control, redirection & pipes |
| [CS251-Asset-Management-Zakat-Calculation-System](https://github.com/Toxkay/CS251-Asset-Management-Zakat-Calculation-System) | Application Development | Asset tracking system with an integrated Zakat calculation engine |

---

## 📊 GitHub Stats

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=Toxkay&show_icons=true&theme=dracula&hide_border=true&count_private=true" alt="Toxkay's GitHub stats" height="165"/>
  <img src="https://github-readme-streak-stats.herokuapp.com/?user=Toxkay&theme=dracula&hide_border=true" alt="Toxkay's GitHub streak" height="165"/>
</div>

<div align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Toxkay&layout=compact&theme=dracula&hide_border=true" alt="Top languages"/>
</div>

---

## 📚 Currently Learning

> [!NOTE]
> **Training & certification tracks**
> - SANS SEC542 — Web App Penetration Testing
> - eWPT — Web Application Penetration Tester
> - NTI CCNA Track — Networking fundamentals
> - ~120 hours of dedicated security training logged so far

---

## 🤝 Contributing

This profile repo is just my landing page, but feedback and contributions on my project repos are always welcome — open an issue or PR directly on:
- [reconw-orchestrator](https://github.com/Toxkay/reconw-orchestrator)
- [Summer-Intern-FInal-Project-NETSEC](https://github.com/Toxkay/Summer-Intern-FInal-Project-NETSEC)

---


## 📡 Contact

| Platform | Link |
| :--- | :--- |
| 🌐 Website / Portfolio | [toxkay.github.io](https://toxkay.github.io) |
| 📧 Email | `karenfadywork@gmail.com` |
| 💼 LinkedIn | `https://www.linkedin.com/in/karen-fady/` |
| 🐦 X / Twitter | `https://x.com/whoAmIwhenNo10` |
| 🎯 TryHackMe / Hack The Box | `tryhackme.com/p/ToxKay` / `https://profile.hackthebox.com/profile/019d05c8-a3c5-701f-b424-940961ed4d31?utm_medium=copy_url` |

<div align="center">

**"The best defense is a good offense."**

⚡ Powered by caffeine and curiosity · 🔐 Secured with best practices

</div>
