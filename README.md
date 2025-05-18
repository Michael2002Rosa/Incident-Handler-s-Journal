# 🛡️ Incident Handler's Journal

This project is a personal cybersecurity learning journal developed during the Google Cybersecurity Certificate program. It documents my progress, practical activities, and reflections related to cybersecurity tools, incident detection, analysis, and response. It serves as both a project portfolio and a record of how my understanding has evolved over time.

---

## 📘 Overview

The journal includes structured entries based on real-world simulations and exercises. Topics include:

- Responding to ransomware incidents
- Analyzing network packet captures
- Using tools like Wireshark, tcpdump, and VirusTotal
- Investigating suspicious file hashes
- Reflecting on learning challenges and breakthroughs

Each entry follows a format that includes:
- **Date**
- **Activity description**
- **Tools used**
- **The 5 W’s (Who, What, Where, When, Why)**
- **Additional notes or reflections**

---

## 📓 Journal Entries

### 🔐 Entry #1 – Responding to a Ransomware Attack  
**Date:** May 10, 2025  
**Summary:**  
In this exercise, I documented a simulated ransomware attack on a healthcare company. The activity involved two major phases:  
1. **Detection & Analysis** – The organization identified the attack and sought external support.  
2. **Containment & Recovery** – Systems were shut down as part of containment, and help was brought in to assist with eradication and recovery.

**5 W’s:**  
- **Who:** A cybercriminal group  
- **What:** Ransomware incident  
- **Where:** Healthcare organization  
- **When:** Tuesday at 9:00 AM  
- **Why:** The attackers gained access through a phishing email and encrypted important files. Their goal was likely financial gain, as a ransom was demanded.

**Notes:**  
- Should companies ever pay ransoms?
- What policies and training could help prevent future attacks?

---

### 🌐 Entry #2 – First Time Using Wireshark  
**Date:** May 11, 2025  
**Summary:**  
I explored Wireshark to analyze captured network traffic. Wireshark is a GUI-based protocol analyzer used to monitor live traffic or review packet capture (PCAP) files.

**Tools Used:** Wireshark  
**Reflections:**  
- Initially overwhelmed by the interface  
- Learned how to filter traffic and spot anomalies  
- Gained a strong appreciation for how powerful network analysis can be in detecting threats

---

### 💻 Entry #3 – Capturing Packets with Tcpdump  
**Date:** May 12, 2025  
**Summary:**  
In this CLI-based activity, I used `tcpdump` to capture and analyze traffic. It works similarly to Wireshark but is operated via the command line.

**Tools Used:** tcpdump  
**Reflections:**  
- Challenging at first due to my limited command-line experience  
- Made mistakes with syntax but worked through them by re-reading instructions  
- Felt accomplished after successfully filtering and reviewing network traffic

---

### 🧪 Entry #4 – Investigating a Malicious File Hash  
**Date:** May 13, 2025  
**Summary:**  
I investigated a suspicious file hash using VirusTotal. The alert originated from an employee's computer after a phishing email was received.

**Tools Used:** VirusTotal  
**5 W’s:**  
- **Who:** Unknown malicious actor  
- **What:** A malicious `.exe` file attached to an email  
- **Where:** A financial services company  
- **When:** 1:20 PM (alert triggered by IDS)  
- **Why:** The employee unknowingly opened the malicious file

**Reflections:**  
- VirusTotal is a fast and reliable tool for verifying file reputations  
- This activity reinforced how phishing attacks remain a significant threat  
- Consider implementing stronger security awareness training for end-users

---

## 🧠 Reflections

### 🧩 Most Challenging Activity  
Learning to use `tcpdump` via the command line was the hardest. I made multiple syntax errors early on, but I learned to slow down, double-check the documentation, and keep trying.

### 🔄 How My Understanding Changed  
Before this course, I had a vague idea about incident detection and response. Now, I understand the structure and phases involved, including preparation, detection, containment, eradication, recovery, and lessons learned. I also learned the importance of tools, clear processes, and teamwork.

### 🚀 Favorite Concept  
Network traffic analysis was by far the most fascinating topic. Capturing and analyzing live packets made the invisible threats visible. I’m excited to dive deeper into network forensics and become more confident using protocol analysis tools.

---

## 🧰 Tools Highlighted
- **Wireshark** – GUI-based packet analyzer  
- **tcpdump** – Command-line traffic capture tool  
- **VirusTotal** – Hash, URL, and file scanning for malware detection

---

### 📜 License  
This project is part of the [Google Cybersecurity Certificate](https://www.coursera.org/professional-certificates/google-cybersecurity).

---
