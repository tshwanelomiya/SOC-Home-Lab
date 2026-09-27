# 🛡️ Cybersecurity Operations & Security Analysis Portfolio

Hands-on cybersecurity portfolio demonstrating practical work in **security monitoring, alert triage, network analysis, intrusion detection, vulnerability assessment, web application security, phishing investigation, incident response, and security reporting**. The portfolio is designed for two audiences: **recruiters and hiring managers** evaluating hands-on cybersecurity capability, and **prospective freelance clients** looking for clearly scoped, authorized security assessment and security-analysis work.

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


## 🎓 Certifications & Training

### Cybersecurity
- **Cybersecurity Fundamentals Certificate**
- **Cybersecurity Operations and Defense Specialist Certificate**
- **Cybersecurity Expert Professional Certificate**
- **Regenesys Cybersecurity Certificate**
- **CompTIA Security+ — In Progress**

### Additional Education
- **Higher Certificate in Business Principles and Practices**
- **Certificate in Accounting Software**

## 👤 Recruiter & Client Overview

### For Recruiters
This portfolio provides evidence of:
- Hands-on cybersecurity laboratory experience
- SOC alert triage and True Positive / False Positive classification
- Network reconnaissance and traffic analysis
- IDS configuration and custom detection rules
- Web application security assessment
- Phishing, IOC, and incident investigation
- Security reporting, remediation, and hardening recommendations
- Practical use of industry-relevant security tools

**Target roles:** SOC Analyst · Cybersecurity Analyst · Junior Security Engineer · Entry-Level Security Operations

### For Freelance Clients
The portfolio demonstrates a structured approach to **authorized** cybersecurity work, including:
- Network and service reconnaissance
- Basic vulnerability and web application assessment
- Network traffic analysis
- IDS/detection configuration and validation
- Phishing and security incident analysis
- Security findings and remediation documentation
- Security hardening recommendations

**Potential engagement areas:** security assessments · vulnerability identification · security monitoring support · phishing/incident analysis · technical security reporting

> **Important:** The projects in this repository are laboratory, training, or simulated engagements. They demonstrate methodology and technical capability and should not be presented as previous commercial client work.

## 🧾 Example Deliverables

A typical authorized assessment or security-analysis engagement can be documented with:
1. **Scope & authorization** — systems, applications, testing boundaries, and objectives
2. **Discovery & assessment** — reconnaissance, service identification, and security testing
3. **Evidence** — relevant screenshots, packet captures, alerts, logs, and technical observations
4. **Findings** — vulnerability or security issue, affected asset, evidence, and potential impact
5. **Detection/analysis** — relevant alerts, IOCs, traffic observations, or investigation findings
6. **Recommendations** — practical remediation and security-hardening actions
7. **Final report** — concise technical and management-facing summary
8. **Retesting** — where agreed, validation that identified issues were addressed

## 🔐 Freelance Engagement Principles

For any real-world work, the engagement should begin with **written authorization and clearly defined scope**. Testing should remain within the agreed targets, methods, and time window.

The portfolio is intended to demonstrate a professional workflow rather than imply production experience that has not been obtained.

**Workflow:** Authorization & Scope → Discovery → Assessment → Evidence → Analysis → Reporting → Remediation → Retesting

## 📂 Featured Work

### 🚨 Suricata IDS & Detection Engineering
Configured Suricata, developed custom detection rules for controlled Nmap and XSS-related activity, investigated signature errors, and validated alerts.

**[View project](projects/suricata-ids/README.md)** · **[View report](Suricata-ids-detection-engineering.pdf)**

### 🕵️ Wireshark Network Traffic Analysis
Captured and analyzed TCP/HTTP traffic generated during controlled web security testing and correlated network observations with IDS activity.

**[View project](projects/wireshark-analysis/README.md)** · **[View report](Wireshark-network-traffic-analysis.pdf)**

### 🔎 Network Reconnaissance
Performed authorized host discovery, port scanning, service enumeration, and attack-surface analysis using Nmap.

**[View project](projects/nmap-reconnaissance/README.md)** · **[View report](Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening/Network%20Reconnaissance.pdf)**

### 🌐 OWASP Juice Shop Security Assessment
Used Burp Suite, Wireshark, and Suricata to investigate controlled XSS activity against the intentionally vulnerable OWASP Juice Shop application.

**[View project](projects/web-application-security/README.md)** · **[XSS report](owasp-juice-shop-xss-assessment.pdf)** · **[Incident report](Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening/OWASP%20Incident%20Report.pdf)**

### 🎣 Simulated Phishing Compromise Investigation
Investigated a simulated attack chain from phishing email through account compromise, containment, recovery, and endpoint hardening.

**[View investigation](reports/phishing-compromise-investigation.md)** · **[Full report](Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening/Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening%20(1).pdf)**

### 📡 Netcat HTTP Protocol Analysis
Manually constructed HTTP requests over TCP to understand application communication at the protocol level.

**[View project](projects/netcat-http-analysis/README.md)** · **[View report](Investigate%20a%20Simulated%20Compromise%20from%20Phishing%20Email%20to%20Endpoint%20Hardening/Netcat%20GET%20request.pdf)**

## 🚨 TryHackMe SOC Alert Triage Simulation

Completed the **TryHackMe SOC Simulator** beginner-level simulation with **100% successful detection/classification**, correctly distinguishing True Positive and False Positive alerts.

The exercise demonstrates practical SOC fundamentals including alert triage, investigation, evidence-based classification, case documentation, and escalation decisions.

**[View SOC Simulator case study](projects/tryhackme-soc-simulator/README.md)** · **[View evidence](evidence/tryhackme-soc-simulator/)**

## 🧪 SOC / Security Operations

My SOC-oriented work includes:

- Alert triage and True Positive / False Positive classification
- TryHackMe SOC simulation with 100% successful completion
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

This repository demonstrates hands-on laboratory and simulated-investigation capability. It does not claim production SOC employment or previous commercial consulting engagements.

---

**Repository:** [SOC-Home-Lab](https://github.com/tshwanelomiya/SOC-Home-Lab)  
**Author:** Tshwanelo Miya
