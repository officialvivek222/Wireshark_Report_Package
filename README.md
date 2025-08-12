# Wireshark Packet Analysis

## Overview
This project demonstrates basic packet capturing and protocol analysis using Wireshark.  
It includes:
- A packet capture file (`.pcap`)
- Screenshots of the Wireshark interface
- A detailed PDF report of the findings

## Files in this Repository
- **Report.pdf** – Final analysis report containing steps, protocols identified, and insights.
- **network_capture.pcap** – Packet capture file containing recorded network traffic (dummy data for demonstration).
- **Screenshots/** – Folder with images showing the capture process and filtered views in Wireshark.
  - `start_capture.png`
  - `http_filter.png`
  - `dns_filter.png`
  - `packet_details.png`

## Objective
The aim is to capture live network traffic, identify multiple protocols, and analyze packet details to improve protocol awareness and hands-on skills.

## Steps to Reproduce
1. Install Wireshark from https://www.wireshark.org/download.html
2. Select your active network interface and start capturing.
3. Perform some internet activity (visit a website, ping a server).
4. Stop capture and apply filters like `http`, `dns`, `tcp`.
5. Save the capture as `.pcap` and analyze.

## Notes
- The provided `.pcap` in this package contains dummy packets for demonstration purposes.
- For a real analysis, run the steps above on your own system.
