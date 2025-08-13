# wireshark-packet-analysis
Using Wireshark to analyze packet

# Wireshark Packet Analysis Project

PROJECT OVERVIEW

This project demonstrates how to capture and analyze network packets using **Wireshark**.  
The goal was to capture live network traffic, filter for HTTP packets, and extract important details such as source/destination IPs and request methods.

TOOLS USED
- **Wireshark** (latest version)
- Web browser for generating network traffic

STEPS TAKEN
1. Installed Wireshark from [https://www.wireshark.org/download.html](https://www.wireshark.org/download.html).
2. Opened Wireshark and selected the active network interface (Wi-Fi/Ethernet).
3. Started capturing packets while visiting a sample website (`example.com`).
4. Applied a filter, "http" to view only HTTP packets.
5. Selected one packet for detailed analysis.
6. Expanded the **Ethernet**, **IP**, **TCP**, and **HTTP** layers in the Packet Details pane.
7. Documented the following:
- **Packet Number**: 3028
- **Source IP**: 192.168.7.10
- **Destination IP**: 13.226.223.188
- **Protocol**: HTTP
- **Request Method**: GET / POST
- **Purpose**: Browser requesting webpage data

FINDINGS
- The analyzed packet was an HTTP GET request from my local machine to the target web server.
- The TCP handshake ensured a stable connection before data transfer.

SCREENSHOTS
<img width="1680" height="1050" alt="wiresh" src="https://github.com/user-attachments/assets/940ea2f3-16a2-4214-b69c-d099a691f1ea" />


<img width="1679" height="1050" alt="http" src="https://github.com/user-attachments/assets/7556abde-9e0b-42d7-baf6-9af99fa83384" />




WHAT I LEARNED
- How to capture live network packets.
- How to filter traffic in Wireshark for specific protocols.
- How to interpret different layers of packet data.

