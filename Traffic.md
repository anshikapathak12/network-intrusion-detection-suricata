
🔍 Traffic Analysis
Opened .pcap file in Wireshark
Applied filters:
ICMP traffic
TCP SYN packets
🚨 Intrusion Detection (Suricata)
sudo suricata -r attack.pcap -l logs/
✍️ Custom Rule
alert icmp any any -> any any (msg:"ICMP Ping Detected"; sid:1000001; rev:1;)
📊 Alerts Generated
Detected ICMP ping traffic
Identified network scanning behavior
Observed Kali Linux activity
🧠 Key Learnings
Packet-level traffic analysis
Intrusion detection using Suricata
Writing custom IDS rules
Understanding real-world attack patterns
📌 Conclusion

This project replicates a real SOC environment where attacks are detected and analyzed using industry-standard tools.
