# Lab Walkthroughs — TryHackMe & Hack The Box Academy

Walkthroughs for 25 rooms and modules I've worked through on **TryHackMe** and
**Hack The Box Academy**.

I write up every box I do. Each PDF here is the full walkthrough: my own notes, my own
screenshots, and the reasoning behind each step, including the bits where I got stuck and had
to back up. I've grouped them by the skill they build rather than the order I did them in.

> Looking for my own engineering work rather than guided rooms?
> **→ [cybersecurity-portfolio](https://github.com/manlikefelo/cybersecurity-portfolio)** — the AD + SIEM home lab I built, attacked, detected, and investigated.

---

## 🔵 Defensive · SOC · Forensics

The blue-team core: triage an alert, read the logs, follow the artifacts.

| Walkthrough | Platform | What it covers |
|---|:---:|---|
| [Junior Security Analyst Intro](walkthroughs/04-defensive-soc/thm-junior-security-analyst-intro.pdf) | THM | SOC tiers, alert triage workflow, when to escalate |
| [Intro to Log Analysis](walkthroughs/04-defensive-soc/thm-intro-to-log-analysis.pdf) | THM | Log sources, parsing, spotting anomalies, building a timeline |
| [Windows Forensics 1](walkthroughs/04-defensive-soc/thm-windows-forensics-1.pdf) | THM | Registry hives, event logs, user activity artifacts |
| [Intro to Digital Forensics](walkthroughs/04-defensive-soc/thm-intro-to-digital-forensics.pdf) | THM | Acquisition, evidence integrity, chain of custody |
| [Intro to Malware Analysis](walkthroughs/04-defensive-soc/thm-intro-to-malware-analysis.pdf) | THM | Static vs. dynamic analysis, extracting IOCs |
| [Threat Intelligence Tools](walkthroughs/04-defensive-soc/thm-threat-intelligence-tools.pdf) | THM | UrlScan.io, Abuse.ch, PhishTool, Cisco Talos |

## 🔴 Offensive · Pentesting

Understanding the attack well enough to detect it.

| Walkthrough | Platform | What it covers |
|---|:---:|---|
| [Attacktive Directory](walkthroughs/03-offensive/thm-attacktive-directory.pdf) | THM | Kerbrute, Impacket, AD enumeration → post-exploitation |
| [OWASP Top 10 (2021)](walkthroughs/03-offensive/thm-owasp-top-10-2021.pdf) | THM | All ten risk categories, hands-on |
| [SQL Injection Fundamentals](walkthroughs/03-offensive/htb-sql-injection-fundamentals.pdf) | HTB Academy | DBMS internals, UNION-based SQLi, exploitation |
| [Attacking Web Apps with Ffuf](walkthroughs/03-offensive/htb-attacking-web-apps-with-ffuf.pdf) | HTB Academy | Directory, subdomain and parameter fuzzing |
| [Metasploit Framework](walkthroughs/03-offensive/htb-metasploit-framework.pdf) | HTB Academy | Module types, payload generation, responsible use |
| [Vulnerability Assessment](walkthroughs/03-offensive/htb-vulnerability-assessment.pdf) | HTB Academy | VA vs. pentest, scanning, prioritising remediation |
| [Intro to Offensive Security](walkthroughs/03-offensive/thm-intro-to-offensive-security.pdf) | THM | Attacker mindset, directory fuzzing with gobuster |

## 🌐 Networking · Recon · Wireless

| Walkthrough | Platform | What it covers |
|---|:---:|---|
| [Passive Reconnaissance](walkthroughs/02-networking-recon/thm-passive-reconnaissance.pdf) | THM | whois, nslookup, dig — OSINT without touching the target |
| [DNS in Detail](walkthroughs/02-networking-recon/thm-dns-in-detail.pdf) | THM | Record types, resolution flow, DNS hierarchy |
| [Introduction to Networking](walkthroughs/02-networking-recon/htb-introduction-to-networking.pdf) | HTB Academy | OSI & TCP/IP, subnetting, proxies, topologies |
| [Layer 2 MAC Flooding & ARP Spoofing](walkthroughs/02-networking-recon/thm-layer2-mac-flooding-arp-spoofing.pdf) | THM | ettercap, arpspoof, macof — L2 attack and defence |
| [WiFi Hacking 101](walkthroughs/02-networking-recon/thm-wifi-hacking-101.pdf) | THM | Aircrack-ng, handshake capture, WPA analysis |

## 🧱 Foundations

Where I started.

| Walkthrough | Platform | What it covers |
|---|:---:|---|
| [Linux Fundamentals](walkthroughs/01-foundations/htb-linux-fundamentals.pdf) | HTB Academy | Shell, permissions, services, system administration |
| [Windows Fundamentals](walkthroughs/01-foundations/htb-windows-fundamentals.pdf) | HTB Academy | CLI, RDP, enumeration on Windows targets |
| [Introduction to Web Applications](walkthroughs/01-foundations/htb-introduction-to-web-applications.pdf) | HTB Academy | Front/back end, HTTP, common web vulnerabilities |
| [Web Application Security](walkthroughs/01-foundations/thm-web-application-security.pdf) | THM | How web apps break, and how to defend them |
| [Python Basics](walkthroughs/01-foundations/thm-python-basics.pdf) | THM | Scripting fundamentals for security automation |
| [Getting Started (Pentesting)](walkthroughs/01-foundations/htb-getting-started-pentesting.pdf) | HTB Academy | Structured pentest methodology, first boxes |
| [Introduction to Hack The Box](walkthroughs/01-foundations/htb-introduction-to-hack-the-box.pdf) | HTB Academy | Recon, enumeration, exploitation, privilege escalation |

---

## What this repo is (and isn't)

These are guided labs. The room gives me a target and a goal, and I work my way through it.
What they show is that I've got the foundations, I've covered a fair bit of ground, and I
actually write things down as I go.

What they're not is building something from nothing. For that, look at the lab I stood up and
attacked myself:

| Repo | What it proves |
|---|---|
| [security-homelab](https://github.com/manlikefelo/security-homelab) | Designing and documenting an AD + Wazuh SIEM lab on 16 GB of RAM |
| [ad-attack-chain](https://github.com/manlikefelo/ad-attack-chain) | Enumeration → exploitation → Domain Admin, with remediation |
| [detection-engineering](https://github.com/manlikefelo/detection-engineering) | Sigma + Wazuh rules that catch those attacks, with a real tuning log |
| [webapp-pentest-juiceshop](https://github.com/manlikefelo/webapp-pentest-juiceshop) | Web pentest with CVSS-scored findings and a client-ready PDF report |
| [ir-threat-hunt](https://github.com/manlikefelo/ir-threat-hunt) | NIST-lifecycle incident response, timelines, threat hunting |

---

## A note on the content

These are my own write-ups. The rooms and modules themselves belong to TryHackMe and Hack The
Box. If you're doing any of these yourself, do yourself a favour and wrestle with the task
first before you read anyone's notes, mine included. That's where the learning actually is.

---

**Felix Githure** · [LinkedIn](https://linkedin.com/in/felix-githure-2a1b91144) · [githure.felix95@gmail.com](mailto:githure.felix95@gmail.com)
