# Hi there 👋

<div align="center">

### Aspiring SOC L1 Analyst · Detection Engineering & Blue Team Security

[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&size=20&duration=3000&pause=800&color=00FF41&center=true&vCenter=true&width=650&lines=Aspiring+SOC+L1+Analyst;Completed+TryHackMe+SOC+Level+1+Path;Building+Intrusion+Detection+%26+Threat+Intel+Tools;Analyzing+telemetry+with+Splunk%2C+Sysmon+%26+Wireshark;Simulating+adversaries+in+home+labs+to+build+detections;Status%3A+Actively+seeking+SOC+L1+%2F+Blue+Team+roles)](https://git.io/typing-svg)

<p align="center">
  <a href="https://tryhackme.com/certificate/THM-BOBFF5XOHL" target="_blank"><img src="https://img.shields.io/badge/TryHackMe-SOC%20Level%201%20Path-00FF41?style=for-the-badge&logo=tryhackme&logoColor=white" alt="TryHackMe SOC Level 1 Path" /></a>
  <a href="https://portfolio200ok.netlify.app/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-00D26A?style=for-the-badge&logo=netlify&logoColor=white" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/manojmohan404/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://t.me/network_error403" target="_blank"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=for-the-badge&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://discord.com/users/1202244509967056957" target="_blank"><img src="https://img.shields.io/badge/Discord-5865F2?style=for-the-badge&logo=discord&logoColor=white" alt="Discord" /></a>
</p>

</div>

---

## 🧭 About Me

I am a **BCA Graduate (2024)** focused on the **blue-team side of cybersecurity**, specializing in SOC operations, detection engineering, threat intelligence, and adversary simulation.

Instead of studying concepts in the abstract, I believe in practical, hands-on security engineering:
- 🧪 **Adversary Simulation & SIEM Hunting:** Building controlled, isolated home-lab environments (VMware, Kali, Windows, Ubuntu) to simulate real-world attacks (Meterpreter, Mimikatz, Hydra) and hunt malicious activity using Sysmon, Wireshark, and Splunk.
- 🛡️ **Defensive Tool Development:** Writing security tools from scratch — including a privacy-first multi-engine threat intelligence platform, a deep packet inspection NIDS, and a multi-service deception honeypot.
- 📜 **Path Completion:** Completed the **TryHackMe SOC Level 1** path, continuously expanding practical capabilities across Splunk SPL, Elastic, Sysmon telemetry, and digital forensics.

---

## 📜 Certifications & Learning Paths

### 🏅 TryHackMe — SOC Level 1 Path
- **Description:** Covers log analysis, SIEM fundamentals, phishing triage, and network/endpoint monitoring for a Tier-1 SOC analyst role.
- **Certificate ID:** `THM-BOBFF5XOHL`
- **Verification:** [View Certificate](https://tryhackme.com/certificate/THM-BOBFF5XOHL)
- **Core Competencies:**
  - **SIEM & Log Analysis:** Event correlation and search queries in Splunk & Elastic
  - **Endpoint Telemetry:** Host monitoring, Sysmon event logging, and Windows Event ID analysis
  - **Network Security:** Packet analysis, protocol inspection, and stream carving using Wireshark & Tcpdump
  - **Incident Triage:** Phishing email analysis, artifact extraction, and OSINT IOC verification
  - **Frameworks:** Attacker TTP mapping using the Cyber Kill Chain and MITRE ATT&CK

---

## 🛠️ Technical Skills & Knowledge

### Tools & Practical Usage
- **Splunk** — Basic use of SPL, `table`, `stats`, and `rex` for log analysis and extracting information such as IP addresses and ports. Worked with Windows logs, SSH logs, and firewall logs, and continue learning more advanced Splunk and security-analysis techniques.
- **Wireshark** — Basic packet analysis, IP/port identification, TCP/UDP/DNS traffic, and TCP conversation analysis.
- **Sysmon** — Basic Windows telemetry analysis using process, network, file, registry, and DNS events.
- **Nmap** — Basic host discovery, port scanning, service identification, and scan-result analysis.
- **PowerShell** — Basic process checking, log analysis, task management, and Windows system commands.
- **Python** — Basic scripting and development of cybersecurity-related tools and projects.
- **Elastic** — Basic log and security-data analysis, event searching, and time-based filtering.
- **Linux** — Basic command-line usage, file management, system commands, process management, services/daemons, and cybersecurity lab work.
- **Windows** — Basic Windows fundamentals, processes, logs, tasks, and endpoint-security concepts.

### Knowledge & Theory
- **CIA Triad** — Confidentiality, Integrity, and Availability fundamentals.
- **Cyber Kill Chain** — Understanding the stages of a cyber attack.
- **MITRE ATT&CK** — Knowledge of attacker tactics, techniques, and procedures.
- **Malware Types & Analysis** — Knowledge of common malware categories and behaviors, with a basic theoretical understanding of static and dynamic analysis approaches.
- **Threat Intelligence** — Basic understanding of indicators, threat data, and attacker activity.
- **Network Security** — Basic understanding of IPs, ports, TCP, UDP, DNS, and network communication.
- **Endpoint Security** — Basic understanding of processes, logs, system activity, and endpoint telemetry.
- **SOC Fundamentals** — Basic understanding of security monitoring, log analysis, detection, and investigation concepts.

---

## 🚀 Featured Security Projects

### 1. 🔍 ThreatScan — Privacy-First Threat Intelligence Platform
> **Latest Build: v2.1.1** *(v3.5 in active development)* | 🌐 [Live Platform (Demo)](https://threat-intelligence-7eza.onrender.com/) | 📄 [Case Study](https://portfolio200ok.netlify.app/pages/threatscan) | 💻 [Repository](https://github.com/forbidden402/Threat-Intelligence)

A privacy-focused Threat Intelligence Platform designed for SOC analysts, enabling rapid multi-engine correlation across URLs, IPs, domains, and file hashes without persisting sensitive query data to disk.
- **Multi-Engine Correlation:** Aggregates real-time reputation and verdicts from VirusTotal, AbuseIPDB, Shodan, abuse.ch (ThreatFox), AlienVault OTX, URLhaus, and MalwareBazaar.
- **Privacy Architecture:** Built with zero-disk storage retention and an automated 24-hour purge policy to protect sensitive incident telemetry.
- **Exportable Triage Reports:** Generates professional SOC incident summary reports in PDF and DOCX formats using ReportLab.
- **Tech Stack:** `Python` · `FastAPI` · `VirusTotal API` · `AbuseIPDB` · `Shodan` · `AlienVault OTX` · `MalwareBazaar` · `ReportLab`

---

### 2. 🛡️ Network Intrusion Detection System (NIDS)
> **Deep Packet Inspection & Real-Time SOC Dashboard** | 📄 [Case Study](https://portfolio200ok.netlify.app/pages/nids) | 💻 [Repository](https://github.com/forbidden402/Network-Intrusion-Detection-System)

A self-hosted, real-time NIDS equipped with deep packet inspection (DPI), a live analyst dashboard, entity forensic profiles, and OSINT-backed threat lookups to monitor local traffic like a Tier-1 SOC analyst watches a SIEM.
- **Deep Packet Inspection (DPI):** Real-time packet parsing and payload inspection across DNS queries, HTTP request/response headers, and ICMP anomaly patterns using Scapy.
- **Entity Forensic Profiles:** Automatic profiling of flagged IPs with enriched OSINT metadata (geolocation, ISP, abuse confidence scores).
- **Interactive SOC Telemetry:** Real-time web dashboard visualizing protocol distributions and threat frequency charts using Chart.js.
- **SIEM Pipeline Integration:** Session-based SQLite persistence with structured CSV export functionality for upstream SIEM ingestion.
- **Tech Stack:** `Python 3.10+` · `Flask` · `Scapy` · `SQLite` · `Chart.js` · `HTML5/CSS3`

---

### 3. 🍯 Honeyport SOC — Deception & Threat Intel Enrichment
> **Multi-Service Deception & Automated IOC Enrichment** | 📄 [Case Study](https://portfolio200ok.netlify.app/pages/honeyport) | 💻 [Repository](https://github.com/forbidden402/honeyport)

A custom-built Python honeypot featuring 4 emulated services designed to capture malicious probe traffic and immediately correlate attacker infrastructure against threat intelligence feeds.
- **Multi-Service Deception:** Threaded asynchronous socket listeners simulating vulnerable **SSH, HTTP, FTP, and Telnet** services.
- **Real-Time IOC Enrichment:** Automatically triggers API lookups against AbuseIPDB, VirusTotal, and Shodan upon inbound connection attempts.
- **Attacker Profiling & MITRE Mapping:** Logs interaction timestamps, payloads, and attacker source IPs into SQLite with mapping to MITRE ATT&CK techniques.
- **Containerized Deployment:** Packaged with Docker for rapid, isolated deployment across perimeter network segments.
- **Tech Stack:** `Python` · `Flask` · `Docker` · `SQLite` · `AbuseIPDB` · `VirusTotal` · `Shodan` · `MITRE ATT&CK`

---

## 🧪 SOC Home Labs & Detection Engineering

### 🔬 Lab 01: Windows SOC Home Lab — Attack Simulation & Detection
> **Adversary Simulation, Sysmon Telemetry & Splunk Threat Hunting** | 📖 [Full Lab Guide](https://portfolio200ok.netlify.app/pages/soc-windows-home-lab) | 💻 [Repository](https://github.com/forbidden402/SOC-Home_lab-s)

An end-to-end adversary simulation and detection engineering lab executed inside an isolated virtual network environment (Kali Linux attacking Windows 10).
- **Adversary Simulation:** Generated and delivered a staged Meterpreter reverse TCP payload, conducted privilege escalation, and dumped LSASS credentials using Mimikatz.
- **Sysmon Telemetry Engineering:** Configured Sysmon to capture critical host-level telemetry:
  - `Event ID 1`: Process Creation (identifying anomalous parent-child relationships and malicious CLI flags)
  - `Event ID 3`: Network Connection (detecting C2 reverse shells and outbound beaconing)
  - `Event ID 10`: Process Access (hunting Mimikatz accessing `lsass.exe` memory)
- **Splunk Threat Hunting:** Ingested Windows Event Logs and Sysmon data into Splunk; crafted SPL queries to reconstruct the attack timeline, identify persistence indicators, and extract actionable IOCs.
- **Environment:** `VMware Workstation` · `Kali Linux` · `Windows 10` · `Metasploit` · `Mimikatz` · `Sysmon` · `Splunk Enterprise` · `Wireshark`

---

### 🔬 Lab 02: SSH Brute-Force Attack & Detection Home Lab
> **Linux Intrusion, auth.log Forensics & SIEM Triage** | 📖 [Full Lab Guide](https://portfolio200ok.netlify.app/pages/soc-ubuntu-home-lab) | 💻 [Repository](https://github.com/forbidden402/soc_ubuntu_home_lab)

A full-lifecycle Linux attack simulation, packet inspection, and SIEM investigation analyzing an external brute-force campaign against an Ubuntu Server.
- **Attack Simulation:** Executed automated password spraying and high-velocity brute-force attempts with Hydra against OpenSSH, followed by Metasploit root persistence testing.
- **Network & Host Forensics:** Inspected raw packet captures in Wireshark to verify authentication failure handshakes; triaged host-level `/var/log/auth.log` records to uncover unauthorized access attempts.
- **Splunk Ingestion & Analytics:** Configured Splunk Universal Forwarder on Ubuntu Server; formulated SPL threat hunts using field extractions (`rex`), aggregation (`stats`), and formatting (`table`) to calculate brute-force thresholds and generate attacker IP blocklists.
- **Environment:** `Ubuntu Server` · `Kali Linux` · `Splunk Enterprise` · `Wireshark` · `OpenSSH` · `Hydra` · `Metasploit` · `Splunk Universal Forwarder`

---

## 🖥️ Workstation Hardening & Dotfiles

### ⚙️ niri + Noctalia Dotfiles
> 📄 [Configuration Details](https://portfolio200ok.netlify.app/pages/niri-dotfiles) | 💻 [Repository](https://github.com/forbidden402/niri_V4_noctalia-dotfiles)

My daily-driver, keyboard-driven Linux workstation configuration for **Fedora Linux**:
- **Wayland Environment:** Built around **niri** (scrollable tiling window manager) and the Noctalia shell.
- **DNS Hardening:** Hardened DNS-over-TLS (DoT) implementation configured via `systemd-resolved` using Quad9 (`9.9.9.9`) for encrypted resolution and malicious domain blocking.
- **Terminal & VPN:** Integrated with Ghostty terminal emulator and ProtonVPN / WireGuard for secure remote research.

---

## 📝 Write-ups & Notes

- 📓 **[TryHackMe SOC L1 Path Write-ups](https://github.com/forbidden402/Tryhackme_soc_L1_path_wrightup-s)** — Modular notes, hands-on findings, and room walkthroughs documenting the TryHackMe SOC Level 1 curriculum.

---

## 🤝 Let's Connect

I am actively seeking **SOC Analyst (L1) / Blue Team / Junior Security Analyst** roles and am always excited to discuss detection engineering, home lab architectures, and threat hunting!

<p align="left">
  <a href="https://portfolio200ok.netlify.app/" target="_blank"><img src="https://img.shields.io/badge/Portfolio-00FF41?style=flat-square&logo=firefox&logoColor=black" alt="Portfolio" /></a>
  <a href="https://www.linkedin.com/in/manojmohan404/" target="_blank"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=flat-square&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
  <a href="https://t.me/network_error403" target="_blank"><img src="https://img.shields.io/badge/Telegram-26A5E4?style=flat-square&logo=telegram&logoColor=white" alt="Telegram" /></a>
  <a href="https://discord.com/users/1202244509967056957" target="_blank"><img src="https://img.shields.io/badge/Discord-5865F2?style=flat-square&logo=discord&logoColor=white" alt="Discord" /></a>
  <a href="https://github.com/forbidden402" target="_blank"><img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" /></a>
</p>

⭐ *If any of my projects or lab write-ups were helpful to you, consider leaving a star!*
