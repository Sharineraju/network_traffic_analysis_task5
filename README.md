# network_traffic_analysis_task5 
## Capture and Analyze Network Traffic using Wireshark  

### 🎯 Objective  
To capture and analyze live network traffic using **Wireshark** and understand how different protocols such as DNS, HTTP, TCP, and ICMPv6 work in real time.

---

### 🧰 Tools Used  
- **Wireshark** – For packet capturing and analysis  
- **Web Browser** – To generate network traffic  

---

### 🧪 Steps Performed  
1. Opened Wireshark and selected the active network interface (Wi-Fi).  
2. Captured live packets while browsing multiple websites.  
3. Applied protocol filters: `dns`, `http`, `tcp`, and `icmpv6`.  
4. Observed packet details including source/destination IPs, ports, and request types.  
5. Saved the capture file as `network_capture_task5.pcap`.

---

### 📊 Observations  
- **DNS** packets resolved domain names to IP addresses.  
- **HTTP** packets showed unencrypted web requests (via neverssl.com).  
- **TCP** handled connection-oriented traffic for reliable data transmission.  
- **ICMPv6** packets were used for IPv6 communication, often for diagnostic and network discovery purposes.  
- Most modern websites use **HTTPS**, making plain HTTP packets rare.

---

### 🧾 Result  
Successfully captured and analyzed multiple protocols using Wireshark.  
Learned to apply filters, identify different types of traffic, and export packet captures.

---

### 📁 Files Included  
- `wifi_traffic_analysis.pcap` – Packet capture file  
- `README.md` – Documentation report
