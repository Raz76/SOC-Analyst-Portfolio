# Cybersecurity Lab Portfolio
Hi, I'm Razvan! I have a background in technical support, hosting, and mail infrastructure troubleshooting. I am pivoting into cybersecurity as a Junior SOC Analyst. This repository is intended to document my own experience as I progress through the TryHackMe SOC Level 1 learning path.

---

## 🛠️ Skills & Tools Covered
* **SIEM / Log Analysis:** Splunk, ELK Stack
* **Network Security:** Wireshark, Tshark
* **Phishing & Email Security:** Header Analysis, SPF/DKIM/DMARC troubleshooting
* **Endpoint & Incident Response:** CyberChef, Windows/Linux forensics

---

## 📈 Featured Lab Write-ups

### Lab 1: [Name of TryHackMe Room - e.g., Splunk: Basics]
* **Objective:** Learned how to ingest, search, and analyze web server logs to locate a malicious brute-force attack.
* **Tools Used:** Splunk
* **Key Steps Taken:**
  1. Filtered data using `sourcetype="access_combined"` to view HTTP requests.
  2. Isolated a massive spike in failed `POST` requests targeting `/wp-login.php`.
  3. Identified the attacker's source IP address and tracked down the compromised user account.
* **Key Takeaway:** Gained solid practice using Splunk search syntax to filter out normal traffic and find specific indicators of compromise (IOCs).

---

### Lab 2: [Name of TryHackMe Room - e.g., Phishing Analysis Part 1]
* **Objective:** Analyzed a suspected malicious email to determine if it was a phishing attempt.
* **Tools Used:** CyberChef, Email Header Analyzers
* **Key Steps Taken:**
  1. Extracted raw email headers and checked SPF, DKIM, and DMARC alignments.
  2. Discovered the sender IP failed SPF checks and masked itself as a trusted hosting provider.
  3. Safely extracted a malicious attachment hash and queried it on VirusTotal.
* **Key Takeaway:** Connected my existing technical support background in mailing systems with automated security analysis to spot email spoofing.

---

## 📝 Template for New Lab Additions
*Copy and paste this empty structure whenever you finish a tough room:*

### [Room Name]
* **Objective:** [What problem were you trying to solve?]
* **Tools Used:** [e.g., Wireshark, Snort, Suricata]
* **Key Steps Taken:**
  1. [Step 1...]
  2. [Step 2...]
* **Key Takeaway:** [What is the most practical thing you learned?]

---

## 🎯 Next Goals
- [ ] Complete the SOC Level 1 Path on TryHackMe
- [ ] Attempt the TryHackMe Security Analyst Level 1 (SAL1) practical exam
- [ ] Connect with European remote security professionals on LinkedIn

---
*Disclaimer: This repository is for educational and training documentation purposes only.*
