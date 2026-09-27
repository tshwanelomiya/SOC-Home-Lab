# 🛡️ Cybersecurity Operations & Security Analysis Portfolio

Hands-on cybersecurity portfolio demonstrating practical work in **security monitoring, alert triage, network analysis, intrusion detection, vulnerability assessment, web application security, phishing investigation, incident response, and security reporting**. The portfolio is designed to support applications for **SOC Analyst, Cybersecurity Analyst, and Junior Security Engineer** roles.

The work documented here was completed in controlled laboratory or simulated environments as part of cybersecurity training and independent hands-on practice.

## 🔎 What This Portfolio Demonstrates

- Security monitoring and alert triage
- Network reconnaissance and service enumeration
- Network traffic and HTTP analysis
- IDS configuration and detection-rule development
- Web application security testing
- Phishing and IOC investigation
- Incident investigation and reporting
- Security hardening recommendations

## 🧰 Technical Toolkit

| Area | Tools |
|---|---|
| SIEM & Monitoring | Splunk, Wazuh |
| Network Analysis | Wireshark, TCPDump |
| Intrusion Detection | Suricata |
| Reconnaissance | Nmap, Netstat |
| Web Security | Burp Suite, OWASP Juice Shop |
| Network Utilities | Netcat |
| Threat Intelligence | VirusTotal |
| Platforms | Kali Linux, Ubuntu, Windows, VMware |
| Security Operations | Alert Triage, Investigation, Escalation |
| Reporting | Incident & Vulnerability Reports |

## 📂 Featured Work

### 🚨 Suricata IDS & Detection Engineering
Configured Suricata, developed custom detection rules for controlled Nmap and XSS-related activity, investigated signature errors, and validated alerts.

**[View project](projects/suricata-ids/README.md)** · **[View report](Suricata.pdf)**

### 🕵️ Wireshark Network Traffic Analysis
Captured and analyzed TCP/HTTP traffic generated during controlled web security testing and correlated network observations with IDS activity.

**[View project](projects/wireshark-analysis/README.md)** · **[View report](Wireshark%20packet%20capture.pdf)**

### 🔎 Network Reconnaissance
Performed authorized host discovery, port scanning, service enumeration, and attack-surface analysis using Nmap.

**[View project](projects/nmap-reconnaissance/README.md)** · **[View report](Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening/Network%20Reconnaissance.pdf)**

### 🌐 OWASP Juice Shop Security Assessment
Used Burp Suite, Wireshark, and Suricata to investigate controlled XSS activity against the intentionally vulnerable OWASP Juice Shop application.

**[View project](projects/web-application-security/README.md)** · **[XSS report](XSS%20VULNERABILITY.pdf)** · **[Incident report](Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening/OWASP%20Incident%20Report.pdf)**

### 🎣 Simulated Phishing Compromise Investigation
Investigated a simulated attack chain from phishing email through account compromise, containment, recovery, and endpoint hardening.

**[View investigation](reports/phishing-compromise-investigation.md)** · **[Full report](Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening/Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening%20(1).pdf)**

### 📡 Netcat HTTP Protocol Analysis
Manually constructed HTTP requests over TCP to understand application communication at the protocol level.

**[View project](projects/netcat-http-analysis/README.md)** · **[View report](Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening/Netcat%20GET%20request.pdf)**

## 🧪 SOC / Security Operations

My SOC-oriented work includes:

- Alert triage and True Positive / False Positive classification
- SIEM investigation concepts
- Phishing investigation
- IOC analysis
- Incident escalation
- Evidence collection
- Incident reporting
- Security recommendations

## 🔬 Lab Environment

Typical lab architecture:

```
                    ┌─────────────────┐
                    │   Kali Linux    │
                    │                 │
                    │ Nmap            │
                    │ Wireshark       │
                    │ TCPDump         │
                    │ Suricata        │
                    │ Burp Suite      │
                    │ Netcat          │
                    └────────┬────────┘
                             │
                             │ Controlled traffic
                             │
                    ┌────────▼────────┐
                    │ Windows Host    │
                    │ OWASP Juice Shop│
                    └─────────────────┘
```

## 💼 Authorized Security Assessment Workflow

For authorized security assessments, the portfolio follows a structured workflow. The examples here are laboratory or simulated work, not claimed commercial engagements:

**Authorization & Scope → Discovery → Assessment → Evidence Collection → Analysis → Reporting → Remediation → Retesting**

See **[Security Assessment Methodology](reports/security-assessment-methodology.md)** and **[Freelance Cybersecurity Services](freelance-cybersecurity-services/README.md)**.

## 📑 Reporting

Security reports in this repository are designed to document:

- Executive summary
- Scope and methodology
- Technical findings
- Evidence
- Indicators of compromise where applicable
- Risk and potential impact
- Detection methodology
- Remediation recommendations
- Security hardening

## 📁 Supporting Case-Study Material

The repository also contains supporting training material and scenario documentation, including the **SafariPay scenario** and the **Simulated Phishing Compromise** case study. These are kept separate from the main project summaries so the portfolio remains easy to navigate.

## ⚠️ Authorization Disclaimer

All security testing documented here was performed against controlled laboratory systems, intentionally vulnerable applications, or simulated scenarios for training and portfolio purposes. No unauthorized systems or networks were tested.

## 🎯 Recruiter Snapshot

**Core strengths:** network analysis, IDS/detection work, vulnerability assessment, phishing investigation, incident documentation, and security reporting.

**Tools:** Splunk, Wazuh, Wireshark, TCPDump, Suricata, Nmap, Burp Suite, Netcat, Kali Linux, Ubuntu, Windows, VMware.

**Development focus:** building deeper end-to-end SIEM/EDR alert-triage investigations and expanding detection engineering depth.

This repository demonstrates hands-on laboratory capability rather than claiming production SOC or commercial consulting experience.

---

**Repository:** [SOC-Home-Lab](https://github.com/tshwanelomiya/SOC-Home-Lab)  
**Author:** Tshwanelo Miya
