## 🔗 Explore the Project

[Firewall Logs](logs/firewall.log)
[Web Server Logs](logs/webserver.log)
[Executive Summary](reports/executive_summary.md)
[Lessons Learned](reports/lessons_learned.md)
[Change Control Plan](reports/change_control_plan.md)
[Evidence Retention](reports/evidence_retention.md)

# incident-recovery-analysis
Cybersecurity simulation project — malware infection via USB, shell access, C2 traffic, and recovery analysis.

# 🛡️ Incident Recovery and Analysis (Simulation)

## 📌 Scenario

A simulated multi-phase cyberattack was conducted against a mid-sized tech company. The infection originated from a USB device, led to remote shell access on a web server, and involved command-and-control (C2) traffic with attempted lateral movement across internal systems.

## 👩‍💻 My Role

**Forensics Specialist & Documentation Lead**

* Conducted forensic log analysis to identify indicators of compromise (IOCs).
* Traced attacker movement through network and application logs.
* Authored all formal documentation, including lessons learned, evidence handling, and system hardening recommendations.

> 🧪 *Note: Log data used in this project was provided by my instructor as part of a cybersecurity training exercise. All analysis, documentation, and response planning are my own work, simulating real-world SOC practices.*

## 🧰 Tools & Techniques Used

* Firewall and Web Server Log Analysis
* MITRE ATT\&CK and Cyber Kill Chain Mapping
* Forensic Utilities: `shred`, `VeraCrypt`, EDR tools, `Tripwire`, registry & autorun inspection
* Secure reimaging and backup validation
* Web server hardening and WAF rule design

## 📋 Summary of Tasks

* Identified infected host (10.0.3.56) and web server compromise (172.64.92.10)
* Mapped attacker techniques: shell upload, RCE, lateral movement attempts
* Documented full recovery plan including:

  * Host isolation
  * Reimaging and patching
  * Hardening and USB restriction
  * File integrity checks and malware validation
* Outlined post-incident verification and lessons learned

## 📁 Project Structure

```
incident-recovery-analysis/
├── README.md
├── logs/
│   ├── firewall.log
│   └── webserver.log
├── reports/
│   ├── executive_summary.md
│   ├── lessons_learned.md
│   ├── evidence_retention.md
│   └── change_control_plan.md
├── diagrams/
│   └── incident_flow.png
└── tools_used.md
```

## ✅ Key Takeaways

* Log interpretation is critical to understanding attack paths.
* Proper documentation and coordination ensure effective incident response.
* Simple oversights (like USB policy or insecure file uploads) can lead to severe breaches.

## 📊 Outcome

Despite being a simulated exercise, this project gave me hands-on experience in post-breach forensic review, eradication strategy, and recovery documentation. It helped strengthen my ability to think like an analyst and report like a professional.

---

> 🔗 Want to see the logs, evidence retention steps, or incident timeline? Check the `logs/` and `reports/` folders for real examples of how I structured my analysis.
