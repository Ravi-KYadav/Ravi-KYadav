# Investigating a Compromised Windows Machine

> **SOC Analyst Portfolio Project**

## Overview
Investigated a simulated compromised Windows endpoint by correlating authentication, privilege, audit-log and network activity.

**Category:** Incident investigation / Windows security  
**Tools / Concepts:** Windows / event analysis / incident response

## What I Did
- Identified suspicious failed-login activity and a subsequent successful login inconsistent with the expected user schedule.
- Identified deletion of audit logs as a potential defense-evasion indicator.
- Investigated sshd.exe activity and considered potential command-and-control communication.
- Documented next-step questions covering privilege escalation, first C2 communication and additional malicious files.

## Evidence
The screenshots below were extracted/rendered from the original project submission. Public-facing evidence has been kept focused on the security-analysis workflow; credential values are redacted where appropriate.

![Project evidence](evidence-01.png)

![Project evidence](evidence-03.png)

## Analyst Takeaways
- Focused on evidence-driven analysis rather than assumptions.
- Documented findings in an analyst/reporting format suitable for SOC workflows.
- Connected technical observations to security impact, prioritization or remediation where applicable.

## Scope & Ethics
This project was completed in a controlled lab / educational environment using supplied datasets, simulated systems or public threat-intelligence material as described by the original submission. No unauthorized systems were targeted.
