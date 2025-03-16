# Network Security Audit & Hardening Report

## Overview
This project documents a **comprehensive network security audit** performed on a home network. The objective was to identify vulnerabilities, assess security risks, and implement **firewall hardening, open port scanning, network traffic monitoring, and automated security monitoring**. The report provides key findings and recommendations for improving network security.

## Key Findings
- **Firewall security was enhanced** using custom UFW rules.
- **No high-risk open ports** detected after a full network scan.
- **Network traffic analysis** showed normal activity but detected **ISP throttling**.
- **Automated security monitoring script successfully logs security events**.

## Tools Used
- **Linux UFW** (Uncomplicated Firewall) – for securing inbound/outbound traffic.
- **Nmap** – for scanning open ports and assessing potential vulnerabilities.
- **Tcpdump & Iftop** – for analyzing real-time network traffic.
- **Bash Scripting** – for automating security monitoring and log analysis.

## Conclusion
This **network security audit** provided valuable insights into the security posture of a home network. By conducting a **firewall security assessment, open port scanning, network traffic monitoring, and automated security monitoring**, we successfully identified vulnerabilities and implemented mitigation measures. The findings confirm that **no critical security risks were present**, but **ISP throttling was detected**, impacting network performance.

Moving forward, enhancing security through **Intrusion Detection Systems (IDS), SIEM integration, and VPN hardening** will further strengthen the network's resilience against cyber threats.

## Next Steps & Future Improvements
- **Implement Intrusion Detection System (IDS)** like Snort for real-time attack detection.  
- **Deploy Splunk SIEM** to correlate logs and detect suspicious activities.  
- **Harden VPN security** to protect remote access and encrypt sensitive traffic.  

