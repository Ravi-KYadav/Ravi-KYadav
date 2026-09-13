# SOC Portfolio Index

This repository is the profile-level case library. The five repositories below are the active, evidence-driven labs; the project folders in this repository preserve earlier case studies and supporting evidence.

## Featured active repositories

| Repository | Focus | Maturity |
|---|---|---|
| [wazuh-siem-home-lab](https://github.com/Ravi-KYadav/wazuh-siem-home-lab) | SIEM deployment, Windows telemetry and alert investigation | Active |
| [soc-alert-triage-practice](https://github.com/Ravi-KYadav/soc-alert-triage-practice) | L1 alert triage and analyst handoffs | Active |
| [phishing-email-analysis](https://github.com/Ravi-KYadav/phishing-email-analysis) | Email security, IOC extraction and verdicts | Active |
| [network-traffic-analysis-wireshark-suricata](https://github.com/Ravi-KYadav/network-traffic-analysis-wireshark-suricata) | Packet analysis and IDS correlation | Active |
| [mitre-attack-threat-intel-mapping](https://github.com/Ravi-KYadav/mitre-attack-threat-intel-mapping) | Threat intelligence and ATT&CK mapping | Active |

## Case-study categories

### 01 — Endpoint & SIEM
- Compromised Windows Machine
- Windows Firewall Log Analysis
- Wazuh SIEM Home Lab

### 02 — Network Security
- Wireshark Packet Analysis
- Nmap + Windows Firewall Lab
- Network Traffic Analysis — Wireshark & Suricata
- SSL/TLS Certificate Analysis

### 03 — Email & Social Engineering
- Phishing Email Analysis
- Phishing Email Analysis Lab

### 04 — Vulnerability Management
- Vulnerability Management with Nessus
- Vulnerability Management Data Analysis

### 05 — Threat Intelligence & ATT&CK
- MITRE ATT&CK Framework Analysis
- Conti Ransomware Threat Report
- NotPetya Incident Response Report
- MITRE ATT&CK Threat Intelligence Mapping

### 06 — Endpoint Security & Credential Security
- EDR Product Evaluation
- Password Security & Hash Cracking Lab

## Evidence convention

Project folders use a consistent lightweight case-study format:

```text
project-name/
├── README.md
├── evidence-01.png
├── evidence-02.png
└── evidence-03.png
```

The active repositories use a more scalable structure:

```text
repository/
├── README.md
├── docs/
├── cases/
└── evidence/
```

## Publication standard

Only authorised lab work, educational material and sanitised evidence should be published. Secrets, credentials, personal data and unnecessary sensitive infrastructure details are excluded.
