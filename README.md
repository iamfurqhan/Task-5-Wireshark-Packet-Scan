# Task 5 - Capture and Analyze Network Traffic Using Wireshark

##  Objective
Capture live network packets using **Wireshark**, identify different protocols, and summarize the findings.

---

##  Tools Used
- **Wireshark** (for packet capture and analysis)
- **Command Prompt / Terminal** (to generate traffic using ping/curl)
- **Web Browser** (to create HTTP/HTTPS traffic)

---

##  Files in this Repo
- `task5_capture.pcap` → Packet capture file
- `README.md` → This report
- `screenshots/` → Screenshots of Wireshark filters and results

---

##  Steps Performed
1. Installed Wireshark and started capture on the active **Wi-Fi interface**.
2. Generated network traffic:
   - Visited websites (`google.com`, `wikipedia.org`).
   - Used `ping google.com` to create ICMP traffic.
3. Captured traffic for ~60 seconds and saved as `.pcap`.
4. Applied filters (`dns`, `http`, `tcp`, ) to view different protocols.
5. Analyzed packet details and summarized the results.

---


