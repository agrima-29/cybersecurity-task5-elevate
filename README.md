# cybersecurity-task5-elevate
Captured and analyzed live network traffic using Wireshark to identify protocols.
# Task 5 – Capture and Analyze Network Traffic Using Wireshark

## Objective
Capture live network packets and identify at least 3 different protocols using Wireshark.

## Tools Used
- Wireshark (Packet Analyzer)

## Steps Performed
1. Installed and launched Wireshark.
2. Started capture on the active network interface (Wi-Fi).
3. Generated traffic by:
   - Visiting websites (e.g., youtube.com, microsoft.com).
   - Running 'ping google.com' in the command prompt.
4. Stopped the capture after ~2 minutes.
5. Applied filters to examine specific traffic types:
   - 'dns'
   - 'tcp'
   - 'tls'

## Protocols Identified

### 1. DNS (Domain Name System)
- Converts domain names (like 'google.com') into IP addresses.
- Common on port 53.
- Example packet: DNS Standard query and response.

### 2. TCP (Transmission Control Protocol)
- Connection-oriented protocol ensuring reliable data transmission.
- Backbone for protocols like HTTP, HTTPS, TLS.

### 3. TLS (Transport Layer Security)
- Provides encrypted communication over HTTPS.
- Observed during secure website browsing.
- Often seen on port 443.

## Outcome
- Understood the basics of packet capturing.
- Learned to filter traffic and identify core internet protocols.
- Improved awareness of encrypted and unencrypted traffic types.
