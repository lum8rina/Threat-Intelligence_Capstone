# 🕵️‍♀️ Threat Intelligence Capstone Project — A1BC(Banking Sector)

## 📌 Overview
This project focuses on **passive information gathering, threat profiling, and risk assessment** for two organizations:
 **A1BC** — Threat actor profiling & MITRE ATT&CK mapping for TA505

The goal is to simulate a real-world threat intelligence workflow:
- Identify relevant cyber threats  
- Profile threat actors  
- Map techniques to the MITRE ATT&CK framework  
- Recommend mitigation strategies

---

## 🛠 Tools & Technologies
- 🔍 **theHarvester** — Domain & email enumeration
- 🌐 **Shodan** — Internet-facing asset discovery
- 🛰 **AlienVault OTX** — Threat intelligence feeds
- 🧪 **VirusTotal** — Malware analysis & file reputation checks
- 📄 **Google Dorking** — Advanced search for exposed data

---

## 🗂 Project Contents
- 📄 `report.pdf` — Full project report with analysis and recommendations
- 🖼 `screenshots/` — Evidence of findings from OSINT tools
- ⚙️ `data/` — Extracted results, logs, and IOC lists
- 📊 `mitre-mapping.xlsx` — Mapping of TA505 techniques to MITRE ATT&CK

---

## 🔍 Key Findings
- Identified **publicly exposed systems** and outdated SSL/TLS configurations
- Discovered **open ports and potential misconfigurations** on key services
- Profiled **TA505** as a financially motivated cybercrime group targeting financial institutions and enterprises
- Linked observed tactics to MITRE ATT&CK techniques including:
  - **Phishing** (T1566)
  - **Credential Dumping** (T1003)
  - **Data Exfiltration Over Web Services** (T1567.002)

---

## 📊 Risk Assessment Summary
| Risk                         | Likelihood | Impact | Status  |
|------------------------------|------------|--------|---------|
| Phishing & Spearphishing     | High       | High   | 🔴 Red  |
| Ransomware Deployment        | Medium     | High   | 🟠 Amber|
| Data Exposure via Misconfig  | Medium     | Medium | 🟡 Yellow|

---

## 🛡 Recommendations
- Implement **phishing-resistant MFA** across all accounts  
- Enforce **regular vulnerability scanning & patch management**  
- Deploy **network intrusion detection** for early anomaly detection  
- Train staff on **social engineering awareness**  

---

## 📸 Sample Screenshots
![theHarvester Results](screenshots/theharvester-results.png)  
![Shodan Host Scan](screenshots/shodan-scan.png)

---

## 📬 Author
**Lum Rina Ngwan**  
📧 rina_lum@yahoo.com  
🌐 [LinkedIn](https://linkedin.com/in/YOUR-LINK)

---
💡 *“Threat intelligence is the bridge between knowing and defending.”*
