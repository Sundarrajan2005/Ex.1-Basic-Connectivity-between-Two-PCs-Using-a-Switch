## Ex. No 1. 	Basic Connectivity between Two PCs Using a Switch

# Date : 23/07/2026	

# NAME: SUNDARRAJAN K

# REG NO: 212223060279

# Objective:

          “To configure and test basic LAN connectivity between two PCs using a switch.”
________________________________________
# Apparatus/Tools Required:

•	Cisco Packet Tracer Software

•	Devices: PCs, Switch, Router, Cables

•	Optional: Wireless Router, Server, Cloud
________________________________________
# Network Topology Diagram:

<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/00f8db6d-44c9-4710-8169-23400a5866a1" />

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
# Output (Screenshots / Ping Results)

<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/d4ea532e-3f7f-4ccc-b4f1-ba534c004122" />
<img width="1600" height="899" alt="image" src="https://github.com/user-attachments/assets/ce1bac0a-3a41-4d97-9ff3-c16e922a3fbb" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/c1ba846d-8ed2-452d-ace6-24e602a26249" />
<img width="1600" height="900" alt="image" src="https://github.com/user-attachments/assets/5b9eeda3-13ca-4cff-a31b-86e8b523e7b5" />



________________________________________
# Result:
“Successfully configured and verified basic LAN communication between two PCs using a switch in Cisco Packet Tracer.”
	
