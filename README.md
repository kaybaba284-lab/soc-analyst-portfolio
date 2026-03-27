![whois 1](https://github.com/user-attachments/assets/d18b0df3-964c-48a8-b36b-974d808f3972)
![whois 2](https://github.com/user-attachments/assets/bf89f0b2-6c15-42fe-9e02-47bc8f0a97d3)
![tls wireshark](https://github.com/user-attachments/assets/3cf973c3-ca94-4084-9724-95f0d24885c6)
#  SOC Analyst Portfolio

## 👤 About Me

I am a cybersecurity analyst focused on **threat intelligence, email security, and network analysis**.

I specialize in analyzing:

* Phishing emails
* Suspicious domains
* IP reputation
* Network traffic using Wireshark

---

## 🛠️ Tools & Technologies

* Splunk (SIEM)
* Kali Linux
* Wireshark
* ClamAV
* Cisco Talos Intelligence
* VirusTotal
* Linux
* VMware

---

## 📂 Projects

### 📧 Email Threat Analysis

* 🔗 [Phishing Case Study](./email-analysis/phishing-case-study.md)
* 🔗 [Advanced Phishing Analysis (SPF/DKIM/DMARC)](./email-analysis/advanced-phishing-analysis.md)

---

### 🌐 IP Investigation

* 🔗 [IP Reputation Analysis](./ip-analysis/ip-investigation.md)

---

### 🧪 Malware Lab

* 🔗 [Malware Detection Lab](./malware-lab/malware-analysis.md)

---

### 📡 Wireshark Network Analysis

* 🔗 [Phishing Traffic Investigation](./wireshark-analysis/network-investigation.md)

---

## 📊 Skills Demonstrated

* Threat Intelligence Analysis
* Phishing Detection
* Email Header Analysis
* DNS & Network Traffic Analysis
* IOC Identification
* Security Investigation Reporting

---

## 📫 Contact

* Email: [your-email@example.com](mailto:your-email@example.com)
* GitHub: https://github.com/kaybaba284-lab

---

## ⚡ Ongoing Improvements

* Adding real-world attack simulations
* Expanding threat hunting scenarios
* Building detection rules

---
# 📧 Advanced Phishing Email Analysis (With Authentication)

## 📩 Email Details

From: [security@micr0soft-support.com](mailto:security@micr0soft-support.com)
Subject: Suspicious Sign-in Attempt

---

## 🔐 Authentication Results

* SPF: ❌ FAIL
* DKIM: ❌ FAIL
* DMARC: ❌ FAIL

### Analysis

* Sender not authorized
* Email integrity compromised
* Violates domain policy

---

## 🎭 Domain Spoofing

Fake Domain:
micr0soft-support.com

Real Brand:
Microsoft

Technique:
Typosquatting (0 instead of o)

---

## 🌐 URL Analysis

https://micr0soft-account-security-alert.com/verify

### Findings:

* Fake domain
* Credential harvesting intent
* Social engineering keywords

---

## 🧠 Conclusion

This email is a **high-confidence phishing attack** due to:

* Authentication failure
* Domain impersonation
* Social engineering tactics

---# 🌐 IP Investigation Report

## 🔍 IP Address

146.75.89.91

---

## 📊 WHOIS Analysis

* Allocated to RIPE NCC
* Part of large IP range (146.75.0.0/16)

---

## 🧠 Analysis Insight

* Not the actual owner
* Likely shared infrastructure (CDN)

---

## ⚠️ Key Finding

IP reputation alone is not enough:

* Legit infrastructure can host malicious content

---

## 🧾 Conclusion

IP is not inherently malicious but must be analyzed in context with:

* Domain
* DNS activity
* User behavior

---
# 📡 Wireshark Network Investigation

## 🎯 Objective

Analyze network activity after phishing link interaction.

---

## 🔍 Findings

### DNS Analysis

* Query: micr0soft-account-security-alert.com
* Response: ❌ No such name (NXDOMAIN)

### Interpretation

* Domain did not resolve
* Possibly inactive or taken down

---

### TLS Traffic

* Destination IP: 146.75.89.91
* Port: 443

### Observation

* Encrypted HTTPS communication
* No payload visibility

---

## 🧠 Assessment

* DNS failure confirms no connection to phishing domain
* TLS traffic likely unrelated

---

## ✅ Conclusion

Phishing attempt confirmed, but no successful network connection established.

---
# 🧪 Malware Detection Lab

## 🎯 Objective

Safely analyze malware in a controlled environment.

---

## 🛠️ Tools

* Kali Linux
* ClamAV
* VMware

---

## 🔍 Activities

* Scanned files using ClamAV
* Generated file hashes
* Identified indicators of compromise

---

## 🧠 Key Learnings

* Malware detection workflow
* Safe handling practices
* Signature-based detection

---

## ✅ Conclusion

Successfully simulated malware detection in a secure lab environment.

---
# 📊 Indicators of Compromise (IOC)

## 📧 Email IOCs

* [security@micr0soft-support.com](mailto:security@micr0soft-support.com)

## 🌐 Domains

* micr0soft-support.com
* micr0soft-account-security-alert.com

## 🌍 IP Address

* 146.75.89.91

---

## 🚨 Threat Type

Phishing (Credential Harvesting)

---

## 🧠 Analyst Note

These indicators are associated with a phishing campaign leveraging domain spoofing and social engineering.

---

<img width="1862" height="866" alt="talos intelligence" src="https://github.com/user-attachments/assets/a1d8972c-bf53-4781-81a6-9fff2db9875d" />
<img width="1757" height="902" alt="virus total" src="https://github.com/user-attachments/assets/849b6043-c974-4f03-aeb1-8aabf7e2f85f" />
![clam scan](https://github.com/user-attachments/assets/6b15f744-b21e-4948-98f4-9075ff1a8b31)
![email](https://github.com/user-attachments/assets/10761007-0eae-4ffc-84e0-93756cf179ed)

    └── ![tls wireshark](https://github.com/user-attachments/assets/0c7ef692-b298-4db6-8a07-140e86b7d944)
![dns wireshark](https://github.com/user-attachments/assets/8273b5f0-3f1e-489d-9598-5fdb05a1cdee)
