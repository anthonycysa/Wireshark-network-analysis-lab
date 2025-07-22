
# 🦈 Wireshark Network Analysis Lab

This project showcases fundamental packet analysis skills using **Wireshark** in a hands-on lab environment. It was built using the **TryHackMe Wireshark 101** room and is designed to simulate real-world network forensics scenarios a SOC Analyst might face.

---

## 🛠 Tools Used

- **Wireshark 4.4.0**
- **TryHackMe AttackBox**
- **Sample `.pcap` files** (Metasploit & TryHackMe)
- Linux (Kali environment via browser)

---

## 🎯 Learning Objectives

- Launch and navigate Wireshark in a secure VM environment
- Capture and analyze DNS queries and ICMP (ping) traffic
- Understand packet structure (Ethernet, IP, ARP, etc.)
- Apply filters and dissect protocol layers
- Build job-ready network forensics fundamentals

---

## 🧪 PCAP Traffic Analysis

Captured traffic included:
- **DNS Lookup:** `ploit.com` query followed by DNS response
- **ICMP Echo Request:** Outbound ping from internal IP to external IP


---


### 🦈 Wireshark Launch

This screenshot shows the Wireshark GUI successfully launched on the TryHackMe AttackBox, with available network interfaces displayed and ready for packet capture.
### 🟦 Wireshark Launch

This screenshot shows the Wireshark GUI successfully launched on the TryHackMe AttackBox, with available network interfaces displayed and ready for packet capture.

![Wireshark Launch](wireshark-launch.jpg)

---

### 🧠 Sample DNS/ICMP Packet Capture

This screenshot shows DNS queries and ICMP echo requests captured and analyzed in Wireshark.

![Sample DNS/ICMP Capture](sample-dns-icmp.jpg)
# 📄 sample-analysis.md

## 🔍 What Was Analyzed
In this lab, I used Wireshark to open `.pcap` files and analyze basic packet data, including:

- **DNS traffic** between internal hosts and name servers  
- **ICMP Echo Request** (ping) packets to external IPs  
- Identified protocols, source/destination IPs, and packet metadata  
- Practiced filtering and dissecting traffic layers in the Wireshark GUI


---

## 🛡 Security Framework Mapping

This project has been aligned with relevant security frameworks:

- 🔗 [MITRE ATT&CK](./mitre-attack.md)
- 🔗 [NIST Cybersecurity Framework](./nist-csf.md)
- 🔗 [PCI DSS](./pci-dss.md)

---

## 💼 Why This Project Matters

This project demonstrates my ability to:
- Work with raw packet data using Wireshark
- Identify and explain common protocols and behaviors
- Build real-world lab environments for continuous learning

It reflects core SOC Analyst skills such as network visibility, detection, and documentation.

---

## ✅ Next Steps

- Continue analyzing new `.pcap` files from hands-on labs
- Enhance analysis depth with HTTP, FTP, and suspicious traffic patterns
- Apply packet investigation techniques to detection engineering

---
