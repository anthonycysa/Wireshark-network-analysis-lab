
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

For the full breakdown of packets and screenshots:
👉 [View `sample-analysis.md`](./sample-analysis.md)

---

## 📸 Screenshots

| Wireshark Launch | Packet Analysis |
|------------------|-----------------|
| ![Launch](./screenshots/wireshark-launch.jpg) | ![Analysis](./screenshots/sample-dns-icmp.jpg) |

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
