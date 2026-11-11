# Control Tower — SOC Incident Investigation (Blue Team)

A three-week blue-team SOC investigation reconstructing a multi-stage security incident at a simulated healthcare provider — "Medira Health" (telemedicine and clinics, ~180,000 patient records) — from log data alone. Final SOC block of the Cybersteps Cyberanalyst program (Module 2).

> **Discipline:** Blue Team / Security Operations · **Environment:** Splunk · Wazuh · n8n · Mail Gateway

## Objective
Detect, triage and reconstruct an intrusion in a regulated, data-sensitive environment using only the evidence available to a SOC — logs, alerts and endpoint telemetry — and turn it into an actionable incident report.

## Environment & tools
- **Splunk** (SIEM) — log search and correlation with SPL
- **Wazuh** (EDR / HIDS) — endpoint detection and host telemetry
- **n8n** (SOAR) — automation of repetitive response steps
- **Mail Gateway** — analysis of e-mail-borne threats

## Approach
Evidence-first: establish visibility across the available log sources, triage alerts, correlate indicators across SIEM and endpoint data, map activity to attacker techniques, and separate signal from noise — then document detection and hardening recommendations.

## Deliverable
A professional incident report in seven sections — Case File, SOC Visibility, Threat Intelligence, Detection & Hardening, Automation, Incident Report, and Coverage Summary — written for both technical and management readers.

## Skills
SIEM (Splunk / SPL) · Wazuh (EDR) · SOAR automation (n8n) · alert triage · incident response · threat intelligence · detection engineering · security reporting

---
*"Medira Health" is a fictional organisation; all data is simulated for the exercise. Full report available on request.*
