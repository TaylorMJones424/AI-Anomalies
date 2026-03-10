# AI-Anomalies
AI Network Anomaly Detection Lab
Overview:
This project demonstrates a machine learning approach to detecting anomalous network traffic using packet captures generated from simulated attacks in a controlled virtual lab environment.

Lab Environment
Kali Linux (attacker)
Windows VM (traffic capture)
Ubuntu host (analysis)
VMware virtual network

Simulated Traffic
The following traffic types were generated:
Normal ICMP traffic (ping)
TCP SYN port scanning using Nmap
SYN flood attack using hping3

Traffic Capture
Network traffic was captured using Wireshark on the Windows VM and exported as CSV files.

Machine Learning Model
The anomaly detection model uses:
Isolation Forest

Features extracted from packet data include:
packet time
packet length
protocol type
source/destination information

Results

The model was able to detect abnormal traffic patterns associated with simulated denial-of-service traffic and scanning behavior.
<img width="1753" height="719" alt="Screenshot (272)" src="https://github.com/user-attachments/assets/8d5ed134-190d-45db-9207-16730f85899e" />
