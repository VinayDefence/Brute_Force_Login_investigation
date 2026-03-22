# 🛡️ FINAL INCIDENT REPORT

## 📌 Incident Name
Brute Force Login Attack


## 📅 Date
21.03.2026


## 👨‍💻 Analyst
VinayDefence


## 📄 Summary
A brute force attack was detected targeting a Windows system. The attacker attempted multiple login combinations to gain unauthorized access.


## 🌐 Source IP
192.168.0.86


## 🎯 Target System
- Windows 11  
- Windows Server  


## 👤 Target Account
Administrator


## 🔍 Findings

- Multiple failed login attempts detected (Event ID 4625)  
- Possible successful login observed (Event ID 4624)  
- Rapid and repeated login attempts identified  
- Suspicious authentication activity from a single source IP  


## ⚠️ Risk Level
High


## 💥 Impact

- Risk of unauthorized system access  
- Potential compromise of administrator account  
- Possible lateral movement within the network  



## 🛠️ Actions Taken

- Blocked attacker IP address  
- Reset compromised account password  
- Enabled Multi-Factor Authentication (MFA)  
- Monitored system for further suspicious activity  


## 🧠 Detection Method

The attack was detected using Wazuh SIEM by analyzing Windows Security Event Logs.

### Key Indicators:
- Event ID 4625 → Failed login attempts  
- Event ID 4624 → Successful login  


## 🏁 Conclusion

The incident was confirmed as a brute force attack targeting the Administrator account. Early detection helped in identifying and mitigating the threat before further damage occurred.


## 📊 Recommendations

- Enforce strong password policies  
- Enable account lockout after multiple failed attempts  
- Implement MFA for all critical accounts  
- Continuously monitor logs using SIEM tools  
