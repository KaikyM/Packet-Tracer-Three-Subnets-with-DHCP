# Three-Subnets-with-DHCP

## Contextualization
I connected two networks with three subnets and two routers. For PCs, I used a DHCP server to assign IPs, and switches as bridges.

## Devices:
- 1 – Crossover Cable
- 8 - Straight-Through Cable
- 4 – PCs
- 2 - Switchs(2960-24TT)
- 2 - Routers(1941)
- 2 - DHCP Servers

## Schematic Project
![image](https://github.com/KaikyM/Three-Subnets-with-DHCP/assets/127446435/fbbdccc1-5bf7-42f7-b628-7778119a8c20)
- [Download This Packet Tracer Project Here](Three-Subnets-with-DHCP.pkt)
- I used Cisco Packet Tracer: https://www.netacad.com/courses/packet-tracer

## Subnets Table
|Subnet Address|Host Address Range|Broadcast Address|Subnet Mask|
|---|---|---|---|
|192.168.0.0|192.168.0.1 - 192.168.0.62|192.168.0.63|255.255.255.192|
|192.168.0.64|192.168.0.65 - 192.168.0.126|192.168.0.127|255.255.255.192|
|192.168.0.128|192.168.0.129 - 192.168.0.190|192.168.0.191|255.255.255.192|
|192.168.0.192|192.168.0.193 - 192.168.0.254|192.168.0.255|255.255.255.192|
