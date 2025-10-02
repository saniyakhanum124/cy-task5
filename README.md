# cy-task5
# Internship Task 5 – Capture and Analyze Network Traffic using Wireshark  

##  Objective  
The objective of this task was to **capture live network packets** and identify basic protocols and traffic types using **Wireshark**.  

---

##  Tools Used  
- **Wireshark** (Free, Open Source)  

---

##  Deliverables  
1. A **packet capture file (.pcapng)**  
2. A **short report of protocols identified** with screenshots
3. A **README.md file overview about my task

---

##  Steps Performed  

1. Installed and launched Wireshark.  
2. Started packet capture on the active network interface(wifi).  
3. Browsed websites (e.g., Mozilla, Firefox) to generate traffic.  
4. Stopped the capture after ~1 minute.  
5. Filtered traffic by protocol (e.g., `tcp`, `dns`).  
6. Identified at least **3 different protocols**:  
   - **TCP** (Transmission Control Protocol)  
   - **DNS** (Domain Name System)  
   - **TLSv1.2** (Transport Layer Security)
   - **HTTP**(HyperText Transfer Protocol)
7. Exported the capture as `.pcapng`.  
8. Summarized findings with screenshots.  

---

##  Screenshots  

### 1. TCP & TLS Analysis  
![TCP Analysis](screenshots/capture_protocol.png)  

- Shows **TCP retransmissions, ACKs, and Keep-Alives**.  
- TLSv1.2 application data is visible (encrypted traffic).  
- Useful for identifying **network latency, retransmissions, and connection handshakes**.  

---

### 2. DNS Analysis  
![DNS Analysis](screenshots/dns_analysis.png)  

- DNS queries from client `192.168.1.11` to DNS server `192.168.1.1`.  
- Queried domains include:  
  - `mozilla.org`  
  - `fastly.net`  
  - `detectportal.firefox.com`  
- DNS requests/response use **UDP Port 53**.  

---

##  Summary of Findings  

- Successfully captured **live traffic** using Wireshark.  
- Identified and analyzed **TCP, DNS, and TLS , HTTP protocols**.  
- Learned how browsers resolve domain names (DNS) before establishing secure connections (TLS).  
- Observed TCP retransmissions and handshake behavior.  

---

##  Outcome  
This task improved my **hands-on packet analysis skills** and built **protocol awareness**, which is essential for network troubleshooting and cybersecurity monitoring.  

---



