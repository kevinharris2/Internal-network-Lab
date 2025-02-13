# 🛡️ Defense in Depth Lab Progress

## 📌 Overview  
This repository documents my progress in building a **Defense in Depth** cybersecurity lab. It includes **network segmentation, attack simulations, monitoring, and response mechanisms** to enhance security posture.

---

## 📂 Lab Architecture  
- **pfSense (Firewall)** - Handles network security, traffic filtering, and segmentation.  
- **Kali Linux (Red & Blue Team)** - Offensive security testing and network monitoring.  
- **Metasploitable (Target System)** - Vulnerable machine for exploitation practice.  
- **Ubuntu (Monitoring & Analysis)** - Used for observation and further analysis.  
- **RHEL (Server Management)** - Reserved for Red Hat Linux study and system hardening.

---

## 🔴 Red Team Tools (Offensive Security)  
| Tool | Purpose |
|------|---------|
| `arpspoof` | Simulates man-in-the-middle (MITM) attacks |
| `urlsnarf` | Captures and analyzes HTTP traffic |
| `Metasploit` | Exploitation framework for testing vulnerabilities |
| `Nmap` | Network scanning for open ports and services |
| `sysctl` | Enables port forwarding for traffic interception |

---

## 🔵 Blue Team Tools (Defensive Security)  
| Tool | Purpose |
|------|---------|
| `arpDetector.py` | Detects ARP spoofing attacks (Implemented) |
| `netdiscover` | Tracks IPs, MACs, and device activity |
| `Wireshark` | Packet capture and deep traffic analysis |
| `sysctl` | IP forwarding management for traffic monitoring |
| Custom Python Scripts | Automates detection for ARP spoofing and attack simulations |

---

## 📸 Screenshots & Documentation  
This section provides **visual documentation** of my lab setup, testing, and findings
![My system so far]


## 📊 Progress Tracker  
| Date | Task | Status |
|------|------|--------|
| 2025-02-01 | Set up pfSense firewall and configured LAN/WAN | ✅ Completed |
| 2025-02-01 | Deployed Kali Linux and tested `arpspoof` attack | ✅ Completed |
| YYYY-02-03 | Implemented `arpDetector.py` for attack detection | ✅ Completed |
| YYYY-MM-DD | Configured additional monitoring tools for log collection and analysis | ⏳ Pending |
| YYYY-MM-DD | Hardened RHEL with security policies and monitoring | ⏳ Pending |

---

## 📈 Findings & Improvements  
### ✅ **Successes**  
- Successfully detected ARP spoofing attacks using **`arpDetector.py`**.  
- Verified firewall rules in **pfSense** to block unauthorized traffic.  

### ⚠️ **Challenges & Next Steps**  
- Need to fine-tune **monitoring alerts** for better log correlation.  
- Implement **host-based security** (endpoint protection and logging).  

---

## 📎 Resources & References  
- [Ethical Hacking A hands-on Introduction to breaking in](https://danielggraham.com/ethical-hacking-a-hands-on-guide-to-breaking-in/)
- [pfSense Documentation](https://docs.netgate.com/pfsense/en/latest/)  
- [Metasploit Cheat Sheet](https://highon.coffee/blog/metasploit-cheat-sheet/)  
- [Wireshark Tutorials](https://www.wireshark.org/docs/)  

---

## 🏆 Goals & Future Enhancements  
- Implement **Zero Trust Architecture** with strict access controls.  
- Integrate **Threat Intelligence Feeds** for proactive defense.  
- Automate **Incident Response Playbooks** for rapid mitigation.  

---

### 🔗 **Connect with Me**  
📌 **GitHub:** [github.com/kevinharris2](https://github.com/kevinharris2)  
📌 **LinkedIn:** [linkedin.com/in/kevin-harris2](https://www.linkedin.com/in/kevin-harris2/)  

---

### ⚔️ **Defense in Depth: Secure, Detect, Respond, Repeat!** 🔥
