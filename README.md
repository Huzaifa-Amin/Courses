# 📚 Courses

Notes and study material from the courses I complete, organised one folder per course.

## Course Index

| Course | Instructor | Platform | Notes | Certificate |
|---|---|---|---|---|
| [Security Testing: Nmap Security Scanning](./Security-Testing-Nmap-Security-Scanning) | Mike Chapple | LinkedIn Learning | [Study guide (DOCX)](./Security-Testing-Nmap-Security-Scanning/Nmap_Security_Scanning_Notes.docx) | [View certificate](https://www.linkedin.com/learning/certificates/0226f53a1ccdd317ce96f6fb5aff53270e782cb95bead540991d3c9e6bfc6390) |

---

## 🔍 Security Testing: Nmap Security Scanning

**Instructor:** Mike Chapple, Teaching Professor at the University of Notre Dame
**Platform:** LinkedIn Learning
**Course link:** [Security Testing: Nmap Security Scanning](https://www.linkedin.com/learning/security-testing-nmap-security-scanning-14221942/)
**Certificate:** [View my certificate](https://www.linkedin.com/learning/certificates/0226f53a1ccdd317ce96f6fb5aff53270e782cb95bead540991d3c9e6bfc6390)

### 📝 Check the notes

👉 [**Nmap_Security_Scanning_Notes.docx**](./Security-Testing-Nmap-Security-Scanning/Nmap_Security_Scanning_Notes.docx)
A 23-page study guide that follows the course in order.

### 🗂️ Folder structure

```text
courses/
├── README.md
└── Security-Testing-Nmap-Security-Scanning/
    └── Nmap_Security_Scanning_Notes.docx
```

### 📖 What the notes cover

| # | Section | Topics |
|---|---|---|
| 0 | Introduction | Why open ports matter, who the course is for |
| 1 | Network Scanning | TCP/IP, three-way handshake, OSI model, IP addressing, ports, ICMP, scanning and the law |
| 2 | Installing Nmap | Getting Nmap onto your system |
| 3 | Scanning with Nmap | Port states, a first scan, multiple targets, IPv6 |
| 4 | Configuring Nmap Scans | Host discovery, DNS options, TCP and UDP scans, port selection, timing templates |
| 5 | Fingerprinting Systems and Services | OS detection, service version detection, the `-A` shortcut |
| 6 | Scan Output | `-oN`, `-oX`, `-oG`, verbose mode |
| 7 | Case Studies | Four live-server challenges, read step by step |
| A | Appendix | One-page command quick reference |

### ⚡ Quick command reference

| Goal | Flag |
|---|---|
| Skip host discovery | `-Pn` |
| TCP SYN / TCP connect scan | `-sS` / `-sT` |
| UDP scan | `-sU --min-rate 500` |
| Fast scan (top 100 ports) | `-F` |
| Specific / all ports | `-p 80,443` / `-p-` |
| Timing template | `-T0` to `-T5` |
| OS detection | `-O` |
| Service version detection | `-sV` |
| OS + version + traceroute + scripts | `-A` |
| Save output | `-oN` / `-oX` / `-oG` |

> ⚠️ **Only scan systems you own or have written permission to test.**

---

### 📌 About these notes

These are personal study notes written while taking the course. All course content and credit belong to **Mike Chapple** and **LinkedIn Learning**. For the full material, take the [original course](https://www.linkedin.com/learning/security-testing-nmap-security-scanning-14221942/). These notes are not legal advice.
