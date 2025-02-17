Cisco Packet Tracer Lab - MAC Address Analysis

Description

This lab is designed to analyze MAC addresses and their behavior in network communication using Cisco Packet Tracer. The focus is on understanding how MAC addresses change at different points in a network when packets travel between devices.

![MAC Address Analysis](https://github.com/user-attachments/assets/5acb63a7-11b9-4a98-8c3a-bd0e1dff9e3b)
![answer](https://github.com/user-attachments/assets/f3c757f4-e387-4a72-bde8-5fe88497cb02)

Devices Used:

Routers: R1, R2, R3

Switches: SW1, SW2

PCs: PC1, PC2, PC3, PC4, PC5, PC6

Network Structure:

Subnetworks:

192.168.1.0/24 (PC1, PC2, PC3, SW1, and R1)

192.168.12.0/24 (Connection between R1 and R2)

192.168.13.0/24 (Connection between R2 and R3)

192.168.3.0/24 (PC4, PC5, PC6, SW2, and R3)

Objectives

Analyze MAC address behavior:

Observe source and destination MAC addresses when PC1 pings PC4.

Identify MAC address changes at each hop along the path.

Verify MAC address transitions using CLI & simulation mode:

Use show mac address-table and show arp commands.

Use Packet Tracer's simulation mode to observe ARP and MAC learning.

Perform similar analysis for other communication scenarios:

When PC1 pings PC3.

When PC4 pings PC1.

Setup Instructions

Open the .pkt file in Cisco Packet Tracer.

Configure IP addresses for PCs and Routers as per the network diagram.

Use ping to test connectivity and initiate ARP resolution.

Enable Packet Tracer Simulation Mode to observe MAC address changes.

Record MAC addresses at each hop in the network path.

Use CLI commands on switches and routers to verify findings.

Expected Outcomes

Understanding of how MAC addresses change as packets traverse routers.

Insight into Layer 2 vs. Layer 3 packet forwarding.

Ability to use simulation mode for network troubleshooting.

Notes

Ensure that ARP processes complete before entering simulation mode.

If pings fail, check routing tables, default gateways, and cable connections.

Author

Created for educational purposes in Cisco Networking Labs.


