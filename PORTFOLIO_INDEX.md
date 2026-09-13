# SOC Portfolio Index

This repository is the profile-level case library. The five repositories below are the active, evidence-driven labs; the project folders in this repository preserve earlier case studies and supporting evidence.

## Featured active repositories

| Repository | Focus | Maturity |
|---|---|---|
| [wazuh-siem-home-lab](https://github.com/Ravi-KYadav/wazuh-siem-home-lab) | SIEM deployment, Windows telemetry, detections and alert investigation | Active |
| [soc-alert-triage-practice](https://github.com/Ravi-KYadav/soc-alert-triage-practice) | L1 alert triage, case management and analyst handoffs | Active |
| [phishing-email-analysis](https://github.com/Ravi-KYadav/phishing-email-analysis) | Email security, IOC extraction and verdicts | Active |
| [network-traffic-analysis-wireshark-suricata](https://github.com/Ravi-KYadav/network-traffic-analysis-wireshark-suricata) | Packet analysis, IDS correlation and network investigations | Active |
| [mitre-attack-threat-intel-mapping](https://github.com/Ravi-KYadav/mitre-attack-threat-intel-mapping) | Threat intelligence, TTP analysis and ATT&CK mapping | Active |

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

## Repository architecture standard

### Active SOC labs

```text
repository/
├── README.md                 # Executive summary + navigation
├── docs/                     # Methodology, architecture and standards
├── cases/                    # Investigation case library + templates
├── detections/               # Detection concepts / playbooks (where applicable)
└── evidence/                 # Sanitised screenshots and evidence standards
```

Each active repository separates **methodology**, **investigation cases**, **detection logic**, and **evidence** so a recruiter can move from the objective to the actual analyst workflow without searching through a long README.

### Legacy / evidence-backed project folders

The original 13 case studies retain a lightweight structure because their selected evidence is already published:

```text
project-name/
├── README.md
├── evidence-01.png
├── evidence-02.png
└── evidence-03.png
```

These projects are progressively being converted into the same structured case-study standard where additional material adds genuine value.

## Evidence convention

A completed case should normally contain:

1. **Scenario / alert** — what started the investigation
2. **Scope** — affected host, user, network or dataset
3. **Evidence** — screenshots, logs, packets or IOCs
4. **Timeline** — important events in chronological order
5. **Analysis** — how the evidence was interpreted
6. **Verdict** — benign / suspicious / true positive / false positive
7. **Severity & impact** — why the finding matters
8. **Action** — close, monitor, escalate, contain or remediate
9. **MITRE ATT&CK** — where relevant
10. **Analyst handoff** — concise next-step summary

## Publication standard

Only authorised lab work, educational material and sanitised evidence should be published. Secrets, credentials, personal data and unnecessary sensitive infrastructure details are excluded.
