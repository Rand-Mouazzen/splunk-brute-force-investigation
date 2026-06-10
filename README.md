# Splunk SIEM & Incident Triage Simulation Lab

## 📌 Project Overview
This project simulates the environment of a **Tier 1 SOC Analyst** investigating an automated brute-force authentication campaign. Using **Splunk Enterprise**, I ingested, parsed, and analyzed raw server logs to build a forensic timeline, map threat indicators, integrate Threat Intelligence lookups, and author a professional incident triage report.

---

## 🛠️ Skills & Technologies Leveraged
* **SIEM Platform:** Splunk Enterprise / Splunk Processing Language (SPL)
* **Threat Intelligence:** Geolocation Analytics, Known-Malicious IOC Matching
* **Framework Alignment:** MITRE ATT&CK Mapping
* **Defensive Tactics:** Log Ingestion, Field Extraction (`eval`, `stats`), Mitigation Engineering

---

## 🔎 Key Investigation Findings
* **Attack Vector:** Automated Brute-Force Authentication Attempt.
* **Geolocations Identified:** High-volume malicious connection traffic verified from **Russia, China, and Nigeria**.
* **Impact Assessment:** Identified successful unauthorized logons (`status=success`) immediately following massive waves of automated failures (`status=failure`).
* **Root Cause:** Critical exposed authentication endpoints lacking Multi-Factor Authentication (MFA) and account lockout controls.

---

## 📂 Repository Contents
* 📄 **[SOC_Analyst_Splunk_Report.pdf](./SOC_Analyst_Splunk_Report.pdf)** - Complete, formal security investigation report including full analysis and architectural recommendations.
* 📊 **[brute_force_simulation_logs.csv](./brute_force_simulation_logs.csv)** - The raw data sets utilized for ingestion inside the Splunk platform.
* 📸 **`/screenshots`** - Visual walk-through of the specific Splunk query interfaces, field extractions, and stats tables.

---

## 📋 License & Usage
This repository is published exclusively for academic, portfolio, and educational evaluation purposes. 

**Public Use Notice:** Visitors, recruiters, and hiring managers are fully authorized to view, stream, read, and download the contents of this repository for skill evaluation, interview preparation, or peer review. 
