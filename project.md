# 🔐 Real-Time Network Intrusion Detection using Suricata

## 📌 Project Overview
This project demonstrates a complete network security lab setup to simulate attacks, capture traffic, and detect intrusions using Suricata IDS.

## 🛠️ Tools Used
- Ubuntu (Victim Machine)
- Kali Linux (Attacker Machine)
- Suricata IDS
- Wireshark
- tcpdump
- Nmap

## ⚙️ Lab Setup
- Created virtual lab using VirtualBox
- Configured NAT Network for communication
- Assigned IPs:
  - Ubuntu: 10.0.2.15
  - Kali: 10.0.2.3

## ⚔️ Attack Simulation
- Performed ICMP ping attack
- Conducted Nmap port scanning

## 📡 Packet Capture
```bash
sudo tcpdump -i enp0s3 -w attack.pcap
