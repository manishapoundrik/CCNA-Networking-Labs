# Network Traffic Analysis Using Wireshark

## 📌 Project Overview

This project analyzes captured network traffic using Wireshark to understand network protocols, endpoints, and communication patterns.

## 🎯 Objectives

* Analyze network packets and protocol distribution.
* Identify IPv4 and IPv6 endpoints.
* Examine TCP and UDP conversations.
* Understand packet counts, traffic volume, and communication flows.

## 🛠️ Tools Used

* **Wireshark** – Network protocol and packet analysis
* **PCAPNG** – Packet capture file format

## 🔍 Analysis Performed

* Protocol Hierarchy Statistics
* Endpoint Analysis (Ethernet, IPv4, IPv6, TCP, UDP)
* TCP and UDP Conversations
* Packet and byte statistics

## 📊 Key Observations

* The capture contains both IPv4 and IPv6 traffic.
* TCP, UDP, TLS, and QUIC traffic are present.
* DNS traffic is visible in the protocol statistics.
* Endpoint and conversation statistics show communication between local and remote addresses.

## 📁 Project Structure

```text
Network-Traffic-Analysis/
├── README.md
├── Network_Traffic_Analysis_Report.pdf
└── screenshots/
    ├── protocol-hierarchy.png
    ├── endpoints.png
    └── conversations.png
```

## ▶️ How to Use

1. Install Wireshark from https://www.wireshark.org/
2. Open the provided PCAPNG file, if included.
3. Navigate to **Statistics → Protocol Hierarchy**.
4. Use **Statistics → Endpoints** and **Statistics → Conversations** to explore the traffic.

## ⚠️ Note

Analyze only network traffic you are authorized to inspect. Remove sensitive IP addresses, credentials, and personal information before publishing files.

## 👩‍💻 Author

Manisha Poundrik
