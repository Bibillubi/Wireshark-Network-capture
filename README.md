# Wireshark-Network-capture
This project demonstrates network packet capture and analysis using Wireshark. Live traffic was captured from the active network interface, filtered by protocols like HTTP, DNS, and TCP, and analyzed to identify communication between client and server, showing protocol interaction and data flow.

# 🌐 Wireshark Network Packet Capture & Analysis  

![Wireshark](https://img.shields.io/badge/Tool-Wireshark-blue?style=flat-square&logo=wireshark)
![Status](https://img.shields.io/badge/Status-Completed-success?style=flat-square)
![Author](https://img.shields.io/badge/Author-Vistruti%20Mahajan-purple?style=flat-square)

---

## 🧩 Overview  
This project demonstrates **network packet capture and analysis using Wireshark**.  
It involves capturing live traffic, filtering by protocols, and identifying communication between client and server.

---

## ⚙️ Requirements  
- 🖥️ Installed **Wireshark** on the system  
- 🌐 Active **internet connection**  
- 🔑 **Administrator privileges** for live capture  

---

## 🚀 Steps Performed  
1. 🔹 Installed **Wireshark** from the official website.  
2. 🔹 Started **live capture** on the active network interface (Wi-Fi/Ethernet).  
3. 🔹 Generated traffic by **browsing websites** and **pinging servers**.  
4. 🔹 Stopped capture after about one minute.  
5. 🔹 Applied **filters** (`http`, `dns`, `tcp`) to view specific traffic.  
6. 🔹 Identified **three key protocols** — **HTTP**, **DNS**, and **TCP**.  
7. 🔹 Exported the captured data as a **.pcap** file.  
8. 🔹 Analyzed and summarized **packet details**.  

---

## 🧠 Summary of Findings  
| Protocol | Description | Purpose |
|-----------|--------------|----------|
| **DNS** | Domain Name System | Resolves domain names to IP addresses |
| **HTTP** | Hypertext Transfer Protocol | Handles web requests/responses |
| **TCP** | Transmission Control Protocol | Provides reliable data transport |

> The analysis confirmed active communication layers within the network stack — from name resolution to reliable data transmission.

---

## 📂 Output File  
- `network_capture.pcap` — exported packet capture file containing all network traffic.

---

## 📘 Conclusion  
Wireshark effectively captured and visualized real-time network traffic.  
The analysis provided insights into **protocol interaction**, **data flow**, and **communication patterns** across different OSI layers.  


---

⭐ **Developed by [Vistruti Mahajan](#)**  
 *Date: October 2025*



