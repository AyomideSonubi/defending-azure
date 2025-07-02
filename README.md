
# 🛡️ Microsoft Defender Incident Hunting Lab

This project demonstrates threat detection, advanced hunting, and incident analysis using Microsoft Defender for Endpoint. It is based on a simulated multi-stage attack and showcases key skills in threat analysis, MITRE ATT&CK mapping, and KQL-based querying.

---

## 📄 Summary

- **Platform:** Microsoft Defender for Endpoint + Azure Logs
- **Tools Used:** KQL, Advanced Hunting, Incident Graph, MITRE ATT&CK
- **Incident:** Credential access, lateral movement, PowerShell abuse, registry tampering

---

## 📊 Key Skills Demonstrated

- Queried and sorted Defender alerts using KQL
- Investigated 17 security alerts and mapped them to 5 MITRE ATT&CK tactics
- Tracked the attack chain using Microsoft’s incident graph
- Identified suspicious PowerShell, `certutil.exe`, and `reg.exe` behaviors
- Analyzed impacted assets and evidence with real-world incident data

---

## 🔍 Screenshots

- `advanced_hunting.png` – AlertInfo KQL query results
- `incident_attack_story.png` – Graph view of attack path
- `kql_query.png` – Aggregated heartbeat query from Azure Logs

---

## 🧠 MITRE ATT&CK Techniques Identified

| Tactic              | Techniques Involved                          |
|---------------------|----------------------------------------------|
| Execution           | PowerShell Cmdlets, script execution         |
| Credential Access   | SAM file export, `reg.exe` misuse            |
| Lateral Movement    | Remote logon attempts                        |
| Defense Evasion     | AMSI tampering, obfuscated scripts           |
| Discovery           | Registry enumeration                         |

---

## 📂 Included Files

- `Microsoft_Defender_Incident_Report.pdf` – Full incident report
- `*.png` screenshots of queries and incident graph

---

## 🛑 Disclaimer

This lab was conducted in a simulated environment and is strictly for educational purposes.

---

## 👨‍💻 Author

Ayomide Sonubi  
🔗 [LinkedIn](https://www.linkedin.com/in/ayomide-sonubi)  
📂 [GitHub](https://github.com/AyomideSonubi)
