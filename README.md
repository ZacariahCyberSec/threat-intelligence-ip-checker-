# threat-intelligence-ip-checker-
SOC project: Detect brute force attacks and enrich IPs using VirusTotal threat intelligence 
🔍 Threat Intelligence IP Checker (SOC Project)

📌 Overview

This project simulates a real-world SOC (Security Operations Center) workflow by detecting suspicious login activity from system logs and enriching IP addresses using threat intelligence.

The script analyzes authentication logs to identify brute-force attempts and verifies whether the detected IPs are malicious using VirusTotal.

---

🚨 Features

- Detects repeated login attempts (Brute Force detection)
- Extracts and counts IP addresses from log files
- Flags suspicious activity based on frequency
- Integrates with VirusTotal API for threat intelligence
- Identifies malicious IP addresses
- Generates a clear security report

---

🛠️ Technologies Used

- Python
- Linux (Kali)
- Regex (IP validation)
- VirusTotal API
- Log Analysis

---

📂 Project Structure

threat-intelligence-ip-checker/
├── threat_intel.py
├── auth.log
├── screenshots/
└── README.md

---

▶️ How to Run

1. Open terminal in project directory
2. Run:

python3 threat_intel.py

---

📸 Screenshots

🔎 Detection Output

"Detection Output" (screenshots/1-detection-output.png)

💻 Code Implementation

"Code" (screenshots/2-threat-intel-code.png)

---

🎯 Key Learning Outcomes

- Practical SOC log analysis
- Threat detection using Python
- API integration for threat intelligence
- Identifying malicious IP behavior

---

⚠️ Note

Replace the API key with your own VirusTotal API key before running the script:

API_KEY = "YOUR_API_KEY_HERE"

---

👨‍💻 Author

Tinashe Zacariah
Aspiring SOC Analyst | Cybersecurity Enthusiast
