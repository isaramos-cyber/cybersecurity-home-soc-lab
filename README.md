# cybersecurity-home-soc-lab
Engineered a virtualized Security Operations Center (SOC) environment to simulate enterprise-level data orchestration, log aggregation, and real-time threat detection using industry-standard tools.

# 🛡️ Cybersecurity Home SOC Lab (Work in Progress)

> ⚠️ This project is currently in progress as I continue building and refining my cybersecurity home lab.

---

## 🧠 Objective

To design and implement a virtual Security Operations Center (SOC) lab environment that simulates real-time threat detection and defensive monitoring using SIEM tools.

---

## 🏗️ Lab Architecture

Kali Linux (192.168.56.11)
↓
Windows VM (192.168.56.12)
↓
Ubuntu SIEM (192.168.56.10)

---

## 🌐 IP Address Scheme

- Ubuntu (SIEM): 192.168.56.10  
- Kali Linux (Attacker): 192.168.56.11  
- Windows VM (Victim): 192.168.56.12  

---

## 🌐 Network Configuration

Each virtual machine is configured with:

- Adapter 1 (NAT): Internet access
- Adapter 2 (Host-only): Internal lab communication

This setup allows safe simulation of attacks within an isolated environment.

---

## 💻 Systems Used

- Kali Linux (Attacker)
- Windows 10 VM (Victim)
- Ubuntu Server (SIEM)

---

## 🛠️ Tools (In Progress)

- VirtualBox (Virtualization)
- Nmap (Network Scanning)
- Splunk Enterprise (SIEM) — *Currently being configured*

---

## 🧪 Current Progress

✔ Virtual machines installed (Kali, Windows, Ubuntu)  
✔ Network configuration (NAT + Host-only)  
✔ Static IP addressing configured  
✔ Basic connectivity between VMs established  

⚠️ In Progress:
- Splunk installation on Ubuntu  
- Log forwarding from Windows  
- SIEM dashboard configuration  

---

## 🔍 Skills Being Developed

- Network configuration and troubleshooting  
- Linux system administration  
- Virtualization (VirtualBox)  
- Cybersecurity lab design  
- SIEM fundamentals (Splunk)  

---

## 🚧 Next Steps

- Complete Splunk installation and setup  
- Forward Windows event logs to SIEM  
- Simulate attacks from Kali Linux  
- Detect and analyze events in Splunk  
- Document attack scenarios and findings  

---

## 📸 Screenshots
Phase 1: Virtual Environment & Network Connectivity
VirtualBox Inventory
Showing Kali, Windows 10, and Ubuntu SIEM instances.

Network Connectivity Test
Successful ping from Kali Linux to the Windows Victim and Ubuntu SIEM.

<img width="1712" height="1002" alt="image" src="https://github.com/user-attachments/assets/fe2c2c59-5c31-48d2-b28d-5ebbd8a2821a" />

<img width="1702" height="1003" alt="image" src="https://github.com/user-attachments/assets/e5b4fe50-0d3e-47ac-af9f-780587f87aaf" />


---

## 📌 Notes

This lab is being built as part of hands-on cybersecurity training focused on SOC analyst skills and real-world threat detection.

---
