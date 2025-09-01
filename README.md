# 🔐 Cybersecurity Projects Hub – @brrowe81

Welcome to my cybersecurity portfolio.  
This repo showcases **hands-on labs, detections, forensic cases, and incident reports** that simulate the daily work of a SOC analyst.  

---

## 📂 Portfolio Sections

### 🖥️ SIEM Detection Lab
- Splunk & ELK detection rules
- Correlation searches & dashboards
- [Go to folder →](./siem-detection-lab)

### 🕵️ Digital Forensics (DFIR)
- Autopsy / Volatility memory analysis
- Disk image triage & case reports
- [Go to folder →](./digital-forensics-lab)

### 🌐 Network Traffic Analysis
- Wireshark packet captures (PCAP)
- Detection of scanning, brute force, exfiltration
- [Go to folder →](./network-analysis)

### ✉️ Phishing Analysis
- Header and payload breakdowns
- IOC extraction and incident reports
- [Go to folder →](./phishing-analysis)

### ⚙️ Cyber Scripts
- Python, Bash, and PowerShell utilities
- Hash lookups, log parsers, automation tools
- [Go to folder →](./cyber-scripts)

---

## 📊 Example Project Cards

### 🔎 Brute Force Detection (Splunk)
- **Scenario:** Windows Server with repeated failed logins  
- **Tools:** Splunk, Event ID 4625 logs  
- **Query:**  
  ```spl
  index=winlogs EventCode=4625 
  | stats count by Account_Name, IpAddress
  | where count > 10
