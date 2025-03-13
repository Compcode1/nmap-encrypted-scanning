This project explored how Nmap detects and interacts with encrypted and unencrypted services across different network configurations.
We tested three scenarios to observe how Nmap responds to varying levels of encryption:
Unencrypted HTTP (Baseline)
Direct HTTPS using TLS
HTTP over SSH Tunnel
The goal was to analyze encryption visibility in Nmap scans and understand how encryption impacts fingerprinting and reconnaissance techniques.The ability to distinguish between encrypted and unencrypted services in NMAP scans is critical in cybersecurity, as it helps identify potential vulnerabilities in how data is transmitted over networks. By observing how encryption methods like TLS and SSH affect NMAP’s fingerprinting capabilities, we can better understand how attackers might exploit misconfigurations or weak encryption practices. This project directly correlates to real-world security assessments, where understanding the visibility and resilience of encryption in scans can aid in vulnerability detection, network hardening, and recognizing attack patterns such as man-in-the-middle attacks or data leakage over insecure channels.
