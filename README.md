
## AIM:
To capture and analyze network traffic using Wireshark in order to observe protocols, packets, and potential anomalies.
## Requirements:
- **Hardware:**
    - Computer with internet access
    - Network adapter (Ethernet/Wi-Fi)
- **Software:**
    - Wireshark (latest stable version)
    - Sample PCAP files (optional for offline analysis)
## Architecture:
```mermaid
flowchart TD
    A[Network Interface Card] --> B[Wireshark Packet Capture Engine]
    B --> C[Packet Decoder & Protocol Analyzer]
    C --> D[Packet Display & Filtering Interface]
    D --> E[Investigator Analyzes Network Data]
    E --> F[Findings: IPs, Ports, Protocols, Anomalies]
```
## DESIGN STEPS:
### Step 1:
Install Wireshark on the system.

### Step 2:
Launch Wireshark and select the network interface (Ethernet/Wi-Fi).

### Step 3:
Start the capture, apply filters (like http, tcp, ip.addr == x.x.x.x) to analyze specific traffic, and stop the capture after observing relevant data.
### Step 4:
**Analyze traffic to identify:**
  - Source & Destination IP addresses
  - Protocols (HTTP, DNS, TCP, UDP, etc.)
  - Suspicious activities (e.g., unusual ports, repeated requests).
## PROGRAM:
Wireshark Packet Capture and Filter Usage

## OUTPUT:
Captured Packets with Protocol Analysis and Detailed Packet Info
<img width="1920" height="1080" alt="Screenshot (148)" src="https://github.com/user-attachments/assets/0a87acd6-59f5-437a-bb7d-ac7d1fcd15bd" />
<img width="1920" height="1080" alt="Screenshot (149)" src="https://github.com/user-attachments/assets/5f196aa5-f7cf-4b61-af78-8406d399da45" />
<img width="1920" height="1080" alt="Screenshot (150)" src="https://github.com/user-attachments/assets/642a352b-9f9e-4678-83f2-21305861321d" />
<img width="1920" height="1080" alt="Screenshot (151)" src="https://github.com/user-attachments/assets/2f2ee4a7-34e4-4123-a081-c09afecc45db" />
<img width="1920" height="1080" alt="Screenshot (152)" src="https://github.com/user-attachments/assets/f36164c1-e860-45f8-b122-797991905189" />
<img width="1920" height="1080" alt="Screenshot (153)" src="https://github.com/user-attachments/assets/54185f5d-fc54-4264-8d59-8058a830ce05" />







## RESULT:
Network traffic was successfully captured and analyzed using Wireshark.
