# 🛡️ SIEM Detection Labs

Hands-on Splunk labs focused on building detections, alerts, and dashboards for common security use cases.

## 📂 Projects
- **[Brute Force Detection](./Brute-Force-Detection/)**  
  Detects excessive failed Windows logons (`EventCode=4625`), flags potential brute-force activity, and includes an alert + dashboard.

<!-- Add future labs below as you build them -->
<!-- - [Suspicious PowerShell Detection](./Suspicious-PowerShell/) -->
<!-- - [Account Lockout Monitoring](./Account-Lockout/) -->
<!-- - [Phishing Triage (SIEM)](./Phishing-Triage/) -->

## 🧠 Skills Demonstrated
- Ingesting Windows Security logs via Splunk Universal Forwarder
- Writing SPL for detections & aggregations
- Building scheduled/real-time alerts
- Creating dashboards for analyst visibility
- Clear documentation with evidence (screenshots, queries)

## 🚀 Getting Started
Each project folder contains:
- `README.md` — objectives, setup, and results
- `spl_query.md` — key SPL used
- Screenshots — evidence of detections/alerts/dashboards

> Tip: Start with **Brute Force Detection** to see end-to-end ingestion → query → alert → dashboard.
