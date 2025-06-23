# Task1-NetworkScan
Port scanning local network using Nmap

# Task 1 – Scan Your Local Network for Open Ports

This task involved scanning my local network using **Nmap** to identify open ports and services.

## 🔧 Tools Used
- Nmap (`-sS` TCP SYN scan)
- Wireshark (optional, for packet inspection)

## 📝 Steps Followed
1. Found my IP range using `ipconfig`
2. Ran: `nmap -sS 192.168.29.0/24`
3. Analyzed output and documented open ports
4. Captured packets in Wireshark and filtered SYN packets

## 📁 Files Included
- `scan_results.txt`: Nmap output
- `wireshark.png`: Wiresharkcapture

## 📌 Summary
The scan found several devices with open ports. Security assessment was performed to identify potential risks.
