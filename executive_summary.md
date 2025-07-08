## Executive Summary

On April 12, 2025, One Technology experienced a coordinated, multi-stage cyberattack. The attack originated from a USB-based malware infection on an internal workstation (host 10.0.3.56) and escalated to compromise the organization’s public-facing web server (172.64.92.10). The attacker gained remote shell access via a vulnerable upload function and attempted command-and-control (C2) communication and lateral movement across the internal network.

As part of the response effort, infected systems were isolated, reimaged, and scanned for persistence mechanisms. Firewall and web server logs were analyzed to trace attacker techniques and identify indicators of compromise (IOCs). The team validated backups, hardened system configurations, and implemented USB usage restrictions to prevent future incidents.

No customer data was exfiltrated. The incident resulted in improved visibility into host behavior, revised access controls, and the deployment of file integrity monitoring tools.

This simulation exercise strengthened incident response readiness, sharpened forensic skills, and reinforced best practices for threat containment, eradication, and recovery.
