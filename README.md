# NIST-CSF-Incident-Report
Incident Report Analysis for a DoS attack using NIST Cybersecurity Framework
NIST CSF Incident Report: DoS Attack Analysis
Project Description

In this project, I analyzed a real-world cybersecurity incident involving a Denial of Service (DoS) attack. I used the NIST Cybersecurity Framework (CSF) to document the event and create a professional response plan. This analysis demonstrates my ability to identify vulnerabilities and suggest hardening techniques for network security.
Analysis Steps (NIST CSF)
1. Identify

    Attack: ICMP Flood (DoS).

    Impact: Internal services (web design, graphic design) were unresponsive.

    Root Cause: Misconfigured firewall with no rate limiting.

2. Protect

    Implemented ICMP Rate Limiting to control incoming traffic.

    Enabled Source IP Verification to prevent spoofing.

    Applied the Principle of Least Privilege (PoLP) to network access.

3. Detect

    Deployed Network Monitoring Tools to find traffic anomalies.

    Integrated IDS/IPS systems to filter suspicious packets.

4. Respond

    Isolated the network and blocked malicious ICMP traffic immediately.

    Shut down non-critical services to save bandwidth for essential operations.

5. Recover

    Restored critical services first to ensure business continuity.

    Updated firewall configurations to a secure baseline.

Skills Demonstrated

    Incident Response

    NIST Framework Application

    Network Hardening

    Vulnerability Assessment
