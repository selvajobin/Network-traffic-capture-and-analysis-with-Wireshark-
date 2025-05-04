# Network-traffic-capture-and-analysis-with-Wireshark
## AIM:
To capture and analyze network packets using Wireshark, in order to inspect data flows, identify protocols, and detect any suspicious or unusual network behavior.

## DESIGN STEPS:
### Step 1:
Install Wireshark using the command:

### Step 2:
Launch Wireshark and select the appropriate network interface for live traffic capture.

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.


## PROCEDURE:
1. Open Wireshark and Select a Network Interface
• Launch Wireshark.
• Select an active interface (like Wi-Fi or Ethernet) to start capturing packets.

2. Start Capturing Packets
• Click the blue shark fin icon or double-click the interface.
• Wireshark will start capturing all real-time traffic.

3. Apply Filters to Focus on Specific Traffic
• Use filters like http, ip.addr == 192.168.1.1, or tcp.port == 80 in the top filter
bar to narrow down results.

4. Analyze Packet Details
• Click on a packet to view its detailed breakdown including frame, Ethernet,
IP, TCP/UDP layers, and data payload.

5. Export or Save the Capture
• Go to File > Save As to store the capture in .pcap format for future analysis.

## OUTPUT:
**Open Wireshark and Select a Network Interface**
![9-0](https://github.com/user-attachments/assets/a5f9668a-300b-4470-83a5-00f04389fd89)


**Start Capturing Packets**
![9-1](https://github.com/user-attachments/assets/23a6c224-78c9-48f9-a19d-0a088f9b04e8)


**Apply Filters to Focus on Specific Traffic**
![9-2](https://github.com/user-attachments/assets/297d2694-793e-48f5-bc5b-243990462133)


**Analyze Packet Details**
![9-3](https://github.com/user-attachments/assets/cac17707-99dc-4a61-baf6-b49c3c9b7c38)

![9-4](https://github.com/user-attachments/assets/787c4592-2eb4-4084-b793-959441543268)


**Export or Save the Capture**
![9-5](https://github.com/user-attachments/assets/01abfb3b-d6a7-4f8d-883c-ed3cb0585f38)

![9-6](https://github.com/user-attachments/assets/96228044-03a5-4f3d-95a2-b735ed2c3486)


## RESULT:
Wireshark was used to successfully capture and analyze real-time network traffic.
