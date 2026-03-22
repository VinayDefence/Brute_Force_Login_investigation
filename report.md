# 🛡️ SOC Project Report

## 📌 Objective
To detect and analyze cyber attacks using :contentReference[oaicite:0]{index=0}.

---

## 🖥️ Lab Setup
- Kali Linux (Attacker)
- Ubuntu Server (Wazuh Manager)
- Windows Server (Victim)
- Windows 11 (Client)

---

## ⚙️ Tools Used
- Hydra
- Wazuh
- Sysmon

---

## ⚔️ Attack Performed
Brute-force attack using Hydra on RDP service.

---

## 🔍 Detection
- Event ID 4625 (Failed login)
- Event ID 4624 (Successful login)

---

## 📊 Results
- Attack detected successfully
- Logs analyzed in Wazuh dashboard

---

## 🏁 Conclusion
Wazuh successfully monitored and detected the attack in real-time.
