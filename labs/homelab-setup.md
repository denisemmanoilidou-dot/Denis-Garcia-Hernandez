# 🖥️ Personal Cybersecurity Home Lab Setup

## 📌 Overview
Design and architecture of my personal virtual environment for network traffic analysis, vulnerability testing, and threat experimentation.

---

## 🛠️ Hardware & Host Specs
- **Host OS:** Windows 11 Home
- **Processor:** Intel Core Ultra 5 125U
- **RAM:** 16 GB LPDDR5x
- **Hypervisor:** Oracle VM VirtualBox / VMware Workstation Player

---

## 🌐 Virtual Machines & Network Setup

### 1. Attacking Machine: Kali Linux
- **Purpose:** Penetration testing, vulnerability scanning, and packet analysis.
- **Tools:** Nmap, Wireshark, Metasploit, Burp Suite.
- **Network Interface:** NAT / Host-Only.

### 2. Practice Target: Metasploitable / Vulnerable OS
- **Purpose:** Intentionally vulnerable environment for controlled exploit practice.
- **Network Interface:** Isolated Host-Only Network (No external internet access).

---

## 🔒 Security Measures
- Target virtual machines are isolated in a **Host-Only virtual adapter** to prevent any accidental network leaks.
- Snapshots created prior to testing for instant state rollback.
