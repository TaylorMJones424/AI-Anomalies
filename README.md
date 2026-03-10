# AI-Anomalies
AI Network Anomaly Detection Lab

Overview
This project demonstrates a machine learning approach to detecting anomalous network traffic using packet capture data generated from simulated attacks in a virtualized lab environment.

Lab Environment
Attacker Machine:
Kali Linux

Target Machine:
Windows VM

Analysis Environment:
Ubuntu
Python
Jupyter Notebook

Simulated Attacks
The following traffic types were generated:
ICMP traffic (baseline normal activity)
TCP SYN port scan using Nmap
SYN flood traffic using hping3
Traffic was captured using Wireshark and exported as CSV files for analysis.

Machine Learning Model
An anomaly detection model was implemented using:
Isolation Forest (scikit-learn)

Features extracted from network packets include:
packet time
packet length
protocol
source/destination IP

Results
The model was able to identify abnormal traffic patterns associated with simulated attacks compared to baseline network behavior.

Tools Used
Kali Linux
Wireshark
Python
Pandas
Scikit-learn
Jupyter Notebook


<img width="1245" height="730" alt="Anomaly Detection" src="https://github.com/user-attachments/assets/de1cabbe-e0ab-46d8-982c-5a1364088bc9" />

