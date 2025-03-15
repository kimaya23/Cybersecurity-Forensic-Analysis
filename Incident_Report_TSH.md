# 📌 Incident Investigation Report - Thornton Software House (TSH)  

## 🛠 **Objective**  
Conduct a forensic investigation to analyze and mitigate a cybersecurity breach at TSH, preserving digital evidence and ensuring minimal business disruption.  

## 🔍 **Investigation Approach**  
1. **Establish Baseline:** Analyzed historical network logs and configurations to identify anomalies.  
2. **Log Analysis:** Used **Splunk** & **Logstash** to detect unauthorized access attempts.  
3. **Network Traffic Analysis:** Captured packets using **Wireshark** to trace suspicious outbound connections.  
4. **System Forensics:** Utilized **Autopsy** & **EnCase** to examine compromised system files.  
5. **Memory Analysis:** Extracted RAM dumps with **Volatility** to detect active threats.  
6. **User Activity Review:** Investigated Windows Event Logs for irregular login patterns.  
7. **Patch Verification:** Scanned vulnerabilities using **Nessus** to assess security gaps.  
8. **Incident Response:** Documented findings and recommended remediation strategies.  

## 🖥 **Tools & Technologies Used**  
- **Volatility** - Memory forensics & malware detection.  
- **Wireshark** - Network traffic analysis.  
- **Autopsy, EnCase** - File system forensics.  
- **Splunk, ELK Stack** - Log correlation & event analysis.  
- **FTK Imager** - Disk imaging & evidence preservation.  
- **Nessus, OpenVAS** - Vulnerability scanning.  

## 📊 **Key Findings**  
✅ Unauthorized login attempts detected via event logs.  
✅ Suspicious outbound connections linked to external IPs.  
✅ Malware-infected executable traced using Volatility analysis.  
✅ Evidence of phishing email leading to credential compromise.  
✅ Outdated patches exploited for system access.  

## 🛡 **Recommendations**  
🔹 Implement **Multi-Factor Authentication (MFA)** for login security.  
🔹 Upgrade to **latest security patches** to mitigate vulnerabilities.  
🔹 Deploy **advanced email filtering** to block phishing attempts.  
🔹 Conduct regular **forensic audits** & cybersecurity awareness training.  
🔹 Strengthen **endpoint security** with AI-driven threat detection tools.  

## 📄 **Supporting Evidence**  
- [Wireshark Packet Capture](network_analysis/Wireshark_Capture.pcap)  
- [Volatility Memory Dump Analysis](memory_analysis/Volatility_Results.md)  
- [Phishing Email Header Analysis](threat_modeling/Phishing_Investigation.pdf)  

## 🔗 **Connect With Me**  
[🔹 LinkedIn](https://www.linkedin.com/in/yourprofile)
