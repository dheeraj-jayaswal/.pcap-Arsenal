<div align="center">

# 📦 pcap-Arsenal

</div>

> *Every packet tells a story. A growing arsenal of PCAP files from hands-on Web App, API & Network penetration testing.*

<div align="center">

![Wireshark](https://img.shields.io/badge/Tool-Wireshark-1679A7?style=flat&logo=wireshark&logoColor=white)
![License](https://img.shields.io/badge/License-CC%20BY%204.0-blue?style=flat)
![Focus](https://img.shields.io/badge/Focus-Network%20Security-red?style=flat)
![Status](https://img.shields.io/badge/Status-Active-brightgreen?style=flat)

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Dheeraj%20Kumar%20Jayaswal-0077B5?style=flat-square&logo=linkedin&logoColor=white)](https://linkedin.com/in/dheerajkumarjayaswal)
[![Location](https://img.shields.io/badge/Location-Indore%2C%20India%20%28Remote%29-FF6B6B?style=flat-square&logo=googlemaps&logoColor=white)](https://github.com/dheeraj-jayaswal)

</div>

---


## 🧭 How This Fits With My Other Repos

| Repository | What's in it |
|---|---|
| **[.pcap-Arsenal](https://github.com/dheeraj-jayaswal/.pcap-Arsenal)** *(this repo)* | Packet captures organized by protocol, for Web/API/Network-layer analysis and learning |
| [From-Dev-To-Attacker](https://github.com/dheeraj-jayaswal/From-Dev-To-Attacker) | My flagship field journal — 67 original write-ups on vulnerability patterns, written from a developer's lens, with enterprise domain-impact framing across Income Tax, Banking, Retail, E-commerce, Freight Logistics, and Education |
| [CICD-Goat-Vapt-Writeup](https://github.com/dheeraj-jayaswal/CICD-Goat-Vapt-Writeup) | Full VAPT writeup against OWASP CICD-Goat — 16 findings including CVE-2024-23897, mapped to the OWASP Top 10 CI/CD Security Risks, with PoCs and interview-ready summaries |
| [From-Pentester-To-Red-Teamer](https://github.com/dheeraj-jayaswal/From-Pentester-To-Red-Teamer) | My structured 24-month roadmap for transitioning from Web/API pentesting into Red Teaming — phases, labs, certifications, and progress tracked openly as I work through it |
| [AppSec-From-The-Trenches](https://github.com/dheeraj-jayaswal/AppSec-From-The-Trenches) | Pentest tools & methodology reference — how I actually use Burp Suite, Nmap, Metasploit, Hydra, Hashcat, and more, plus my WAPT methodology |
| [API-From-The-Trenches](https://github.com/dheeraj-jayaswal/API-From-The-Trenches) | Deep-dive API security series — OWASP API Top 10 coverage, BOLA, JWT attacks, GraphQL testing, full methodology |
| [Bug-Bounty-Hunting-Companion](https://github.com/dheeraj-jayaswal/Bug-Bounty-Hunting-Companion) | Real, publicly-disclosed bug bounty reports broken into reproducible checklists |
| [DarkWeb-From-The-Trenches](https://github.com/dheeraj-jayaswal/DarkWeb-From-The-Trenches) | Threat intelligence & dark web OSINT methodology — credential leak monitoring, ransomware tracking, pre-engagement TI |

---


## 📖 About This Repository

**pcap-arsenal** is a curated collection of Wireshark packet captures (.pcap / .pcapng) organized by network protocol and security topic. These captures are sourced from real-world lab environments, ethical hacking engagements, and controlled network simulations.

This repository is intended for:
- 🔐 Penetration Testers & Ethical Hackers
- 🧑‍💻 Network Security Analysts
- 🎓 Security Learners & Researchers
- 🛡️ SOC Analysts sharpening detection skills

> ⚠️ **Disclaimer:** All packet captures in this repository are collected from authorized lab environments and ethical hacking engagements only. This repository is strictly for educational and research purposes. Unauthorized network interception is illegal.

---

## 🗂️ Repository Structure

```
pcap-arsenal/
│
├── 802.1q/                  # VLAN Tagging — trunk traffic, tagged frames
├── 802.1x/                  # Port-based Network Access Control (NAC)
├── ARP/                     # Address Resolution Protocol — ARP spoofing, poisoning
├── BGP/                     # Border Gateway Protocol — session setup, route updates
├── GRE/                     # Generic Routing Encapsulation — tunneling traffic
├── HSRP/                    # Hot Standby Router Protocol — gateway redundancy
├── IGMPv2/                  # Internet Group Management Protocol — multicast joins
├── IPv6/                    # IPv6 traffic — NDP, ICMPv6, dual-stack behavior
├── ISE/                     # Cisco ISE — RADIUS auth, policy enforcement flows
├── IS-IS/                   # Intermediate System to Intermediate System routing
├── MTU-MSS-FRAG/            # MTU discovery, MSS negotiation, fragmentation
├── native-vs-normal/        # Native VLAN vs normal VLAN traffic comparison
├── OSPF/                    # Open Shortest Path First — LSA, neighbor adjacency
├── PIMv2/                   # Protocol Independent Multicast v2
├── Ping/                    # ICMP Echo — latency, TTL analysis, ICMP tunneling
├── QoS/                     # Quality of Service — DSCP marking, traffic shaping
├── Spanning-Tree/           # STP — BPDU frames, topology changes, root election
├── SSL/                     # SSL/TLS handshakes — cipher suites, cert analysis
├── TCP/                     # TCP fundamentals — handshake, retransmission, flags
├── Traceroute/              # Path discovery — UDP/ICMP traceroute behavior
└── vxlan-flood-learn/       # VXLAN overlay — BUM traffic, MAC learning, flood behavior
```

---

## 🔍 Topic Highlights

| Folder | Protocol / Topic | Security Relevance |
|---|---|---|
| `802.1q` | VLAN Tagging | VLAN hopping attacks |
| `802.1x` | NAC / EAP | Auth bypass, rogue device detection |
| `ARP` | Layer 2 Resolution | ARP spoofing, MITM |
| `BGP` | Routing Protocol | BGP hijacking, route leaks |
| `GRE` | Tunneling | Covert channels, tunnel abuse |
| `HSRP` | Gateway Redundancy | HSRP hijacking |
| `IGMPv2` | Multicast | Multicast flooding |
| `IPv6` | Next-gen IP | NDP spoofing, rogue RA |
| `ISE` | Cisco NAC | RADIUS traffic, policy bypass |
| `IS-IS` | Routing Protocol | Routing table manipulation |
| `MTU-MSS-FRAG` | Fragmentation | Fragmentation-based evasion |
| `native-vs-normal` | VLAN Behavior | Double tagging attack |
| `OSPF` | Routing Protocol | OSPF injection, neighbor spoofing |
| `PIMv2` | Multicast Routing | Multicast abuse |
| `Ping` | ICMP | ICMP tunneling, recon |
| `QoS` | Traffic Marking | QoS abuse, priority manipulation |
| `Spanning-Tree` | L2 Loop Prevention | STP root bridge attack |
| `SSL` | Encrypted Traffic | TLS downgrade, weak ciphers |
| `TCP` | Transport Layer | SYN floods, session hijacking |
| `Traceroute` | Path Discovery | Network mapping, TTL abuse |
| `vxlan-flood-learn` | Overlay Networking | BUM flooding, VXLAN misconfig |

---

## 🛠️ Tools Used

| Tool | Purpose |
|---|---|
| **Wireshark** | Primary packet capture & analysis |
| **tshark** | CLI-based packet filtering & export |
| **tcpdump** | Lightweight capture on Linux |
| **GNS3 / EVE-NG** | Network lab simulation |
| **Scapy** | Custom packet crafting |

---

## 📌 How to Use

1. **Clone the repo**
   ```bash
   git clone https://github.com/YOUR_USERNAME/pcap-arsenal.git
   cd pcap-arsenal
   ```

2. **Open any .pcap file in Wireshark**
   ```bash
   wireshark 802.1q/capture.pcap
   ```

3. **Filter traffic using tshark**
   ```bash
   tshark -r SSL/tls-handshake.pcap -Y "tls.handshake"
   ```

---

---


## 🧠 Testing Philosophy

> *"The best penetration testers think like developers first and attackers second. If you understand why code was written a certain way, you'll always find more than a scanner ever will."*

I approach every engagement in three phases:

**1. Understand before you attack** — Read the application. Use it as a real user. Understand the business logic before touching a single tool.

**2. Manual first, tools second** — Automated scanners find what they're configured to find. The interesting bugs are always found by thinking, not scanning.

**3. Report like a developer** — A finding that developers can't understand or reproduce is a finding that doesn't get fixed.

---


## 👤 About Me

- **Name** — Dheeraj Kumar Jayaswal
- **Role** — Principal Penetration Tester, VikingCloud (previously Technology Lead – Offensive Security, Infosys Limited)
- **Focus** — Web Application & API Penetration Testing
- **Experience** — 16+ years in IT · 9+ years in Offensive Security
- **Edge** — Former full-stack developer (ASP.NET / SQL Server) — I think like a developer, attack like a hacker
- **Domains** — Income Tax · Banking · Retail · E-commerce · Freight Logistics · Education

---


## 🏅 Certifications

| Certification | Issuer | Status |
|---|---|---|
| Certified Ethical Hacker (CEH) | EC-Council | ✅ 2021 |
| AWS Certified Solutions Architect – Associate | Amazon Web Services | ✅ 2022 |
| AWS Certified Cloud Practitioner | Amazon Web Services | ✅ 2022 |
| Executive Certificate in Cyber Security | IIT Kanpur | ✅ 2026 |
| OSWE — OffSec Web Expert (OSCE3 track) | OffSec | 🔄 In Progress |

**Future direction — Red Teaming:** OSCP → CRTO → OSEP, CRTP, CRTL, CRTE

---


## 📄 License

[![License](https://img.shields.io/badge/license-CC%20BY%204.0-blue)](LICENSE.md)
[![Last Commit](https://img.shields.io/github/last-commit/dheeraj-jayaswal/.pcap-Arsenal)](https://github.com/dheeraj-jayaswal/.pcap-Arsenal/commits/main)

⭐ If this helped you, consider starring the repo — it helps others find it too.

---


## 🤝 Connect

[LinkedIn](https://linkedin.com/in/dheerajkumarjayaswal) — open to consulting, collaboration, and security discussions.

---


<div align="center">

*Every packet tells a story — this is where I keep the ones worth retelling.*

**#Wireshark · #NetworkSecurity · #AppSec · #PenTest · #OffensiveSecurity**

</div>
