# Cisco-Retail-Chain-Network-System

# 1. Introduction
This project was developed in Cisco Packet Tracer as a simulation of a real-world network for a
retail store chain. The scenario involves a centralized Headquarters (HQ) connected to five
branch offices, each of which is independently functional but interconnected to support centralized
services and inter-office communication.
The goal of this simulation was not only to show that devices can connect and ping each other but
also to design a modular and realistic network infrastructure that mimics how retail businesses
operate across multiple locations.

# 2. Project Goals
+ Simulate a full-fledged WAN connecting HQ with multiple branch networks.
+ Establish communication between all end devices using proper IP addressing and routing.
+ Emphasize scalability, proper subnetting, and logical grouping of devices.
+ Ensure a clean layout, both visually (in Packet Tracer) and structurally (through IP planning and topology).
+ Keep the design easy to troubleshoot and expand, mimicking how network engineers handle real projects.

# 3. Network Topology & Device Configuration

# a. Topology Breakdown:
+ Headquarters (HQ):
- Acts as the main control hub.
- Hosts the core router, a central switch, and multiple PCs simulating admin, finance,and IT departments.
- Contains entry and exit points for network traffic flowing to and from the branches.

# • Branch Offices (1 to 5):
+ Each has one router connected back to the HQ.
+ Internally, each branch uses a multilayer switch and a standard switch to connect 5–8 PCs.
  
# b. Devices and Connections:
+ Devices:
- Routers: Cisco 2811 routers were selected for all six locations.
- Switches: 3560 Multilayer switches for routers and Standard 2960 switches for LAN environments.
- Servers: Web, file, and dns servers(3 in total) connected in HQ (which can be accessed remotely by other connected branches as well.
- End Devices: Generic PCs (8 per branch, 12 in HQ).

+  Connections:
- PCs to switches: Copper Straight-through
- Switches to routers: Copper Straight-through
- Inter-router links: Serial DCE/DTE cables



----> For further details about this project and the iP Route table you can refer to the given documentation pdf given below:
[CCN_lab_project_documentation_pdf.pdf](https://github.com/user-attachments/files/21508693/CCN_lab_project_documentation_pdf.pdf)
