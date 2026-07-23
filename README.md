## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch
# Date : 23/07/2026		

# Objective:

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required:

•	Cisco Packet Tracer Software

•	Devices: PCs, Switch, Router, Cables

•	Optional: Wireless Router, Server, Cloud

________________________________________
# Network Topology Diagram:

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/12248c3f-379d-4d29-ac1a-84993968b4e1" />


________________________________________
# IP Addressing Table (if applicable)

Device Name	Interface	IP Address	Subnet Mask
PC0	NIC	192.168.1.2	255.255.255.0
PC1	NIC	192.168.1.3	255.255.255.0
Router0	Fa0/0	192.168.1.1	255.255.255.0
________________________________________
# Procedure:

Step-by-step commands/configurations.
Example:
1.	Open Cisco Packet Tracer and add two PCs and one Switch.
2.	Connect the PCs to the switch using straight-through cables.
3.	Assign IP addresses to the PCs.
4.	Use the ping command to verify connectivity.
________________________________________
# Commands Used (if any)

For PC IP assignment:<br>
nginx<br>
CopyEdit<br>
Desktop > IP Configuration > Enter IP: 192.168.1.2 / Subnet: 255.255.255.0<br>
For Router Configuration (CLI):<br>

________________________________________
# Output (Screenshots / Ping Results):

<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/674dfe0d-7896-4c36-b9cc-626f4162e01f" />

<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/64107f99-705a-4d3b-bf31-0bcd92942b79" />

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/f1b050aa-0da7-4b0d-882c-9c66c88acb9d" />




________________________________________
# Result:

“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
