# MITRE ATT&CK Mapping – Wireshark Network Analysis Lab

This file maps observed network-based attacks and techniques in the Wireshark lab to the MITRE ATT&CK Framework.

| MITRE Technique | Technique ID | Description | Wireshark Use Case |
|------------------|--------------|-------------|---------------------|
| Command and Scripting Interpreter: PowerShell | T1059.001 | Adversaries use PowerShell for execution | Analyzing .ps1 script downloads or command/control patterns |
| Credential Dumping | T1003 | Capturing credentials from memory or network | Detecting NTLM hash or Kerberos tickets in traffic |
| Data Exfiltration Over Unencrypted/Obfuscated Non-C2 Protocol | T1048.003 | Sending stolen data over HTTP, FTP, etc. | Monitoring large FTP uploads or HTTP POST anomalies |
| DNS Tunneling | T1071.004 | Using DNS to encode and exfiltrate data | Reviewing unusual DNS request sizes and frequencies |
| Lateral Movement via SMB | T1021.002 | Using SMB to access remote systems | Tracking SMB sessions and credential handshakes |
| Network Sniffing | T1040 | Capturing network traffic to gather intel | Demonstrated with Wireshark capturing cleartext logins |
| Ingress Tool Transfer | T1105 | Downloading tools from attacker-controlled sources | Identifying suspicious download patterns |
| Application Layer Protocol: Web Protocols | T1071.001 | Using HTTP/S for C2 | Viewing unencrypted HTTP C2 traffic in PCAPs |

🧠 **Why it matters**: Understanding how attack techniques manifest in network traffic is a key SOC skill. Wireshark enables visibility into attacker behavior.