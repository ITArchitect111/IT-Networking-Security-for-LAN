# IT-Networking-Office-LAN

This project demonstrates a complete network topology setup using:
- **3 Router**
- **1 Firewall**
- **5 Switches**
- **1 Cloud**
- **1 Modem**
- **4 Servers**
- **End Devices**

The use Configuration use was **Dynamic Host Configuration Protocol (DHCP)**, **Virtual Local Area Network(VLAN)**, **Open Shortest Path First(OSPF)** , **Hot STanbdy Routing Protocol(HSRP)**,and **Spanning Tree Protocol(STP)**, **File Transfer Protocol(FTP), **Hypertext Transfer Protocol Secure(HTTPS)**, **Simple Mail Transfer Protocol(SMTP)**, **Post Office Protocol(POP)**,"Port Address Translation(PAT)**, **Access List**, **Secret Shell(SSH)**, **Network Time Protocol(NTP)**, and **Domain Name System(DNS)**. Designed and simulated using **Cisco Packet Tracer**, this setup is ideal for Implementing the past projects in real life topology or infrastructure.

---

## Project Objectives
- Design and Implement an Enterprise Network Topology to develop a complete and scalable network infrastructure integrating routers, switches, servers, and end devices that emulate a real-world enterprise environment.
- Implement Dynamic IP Addressing using DHCP to automate IP address assignment across all network segments except for Server VLAN, minimizing manual configuration and IP conflicts.
- Segment Network using VLANs To separate departments (Front Desk, Management, Server Room, CEO Office, etc.) into logical networks, improving security, manageability, and performance.
- Ensure Redundancy and Load Balancing with HSRP and LACP to maintain continuous network availability and optimize link utilization through Hot Standby Router Protocol (HSRP) and Link Aggregation Control Protocol (LACP).
- Optimize Routing through OSPF to establish efficient dynamic routing between routers, ensuring fast convergence and optimal path selection.
- Enhance Network Security and Remote Access using SSH and ACLs to secure administrative access through encrypted remote sessions (SSH) and restrict unauthorized traffic via Access Control Lists (ACL).
- Implement Network Services for Enterprise Operations to deploy essential services such as:
- DNS for domain resolution
- FTP/HTTP/HTTPS for web and file sharing
- NTP for synchronized time management
- Email (SMTP/POP) for communication
- Integrate VoIP Telephony System To establish IP-based voice communication within departments using Cisco IP Phones and Call Manager (Telephony Server).
- Apply PAT for Internet Connectivity to allow multiple internal devices to access external networks securely using Port Address Translation.
- Ensure Loop-Free Network through STP to prevent broadcast storms and redundant path loops using Spanning Tree Protocol across switch networks.
- Simulate Real-World ISP Connection to connect the enterprise network to the Internet through an ISP cloud and modem, emulating a complete WAN setup.
- Evaluate Network Performance and Reliability to test and verify connectivity, redundancy, routing efficiency, and service availability under simulated conditions.
---

## Repository Contents

# Configurations/
- **Internet.txt**
- **Gateway.txt**
- **Office.txt**
- **Standby.txt**
- **Access.txt**
- **Server.txt**
- **FrontDesk.txt**
- **Management.txt**
- **CEO.txt**

# IT Networking Source File/
- **IT Network 5(Office LAN Architecture).pkt**

# Overview
![Topology](Overview/IT_Network_5.png)

# README.md

## Tools Used
- **Cisco Packet Tracer** – for simulation and design
- **Text Editor** – for writing and reviewing CLI configs

---

## How to Use
1. Open the `IT Network 5(Office LAN Architecture).pkt` file using **Cisco Packet Tracer**.
2. Check Network devices if they have DHCP, VLANs, and Telephony.
3. Analyze the Topology and try to ping each devices.
4. Test communication via IP Phones across the network.
5. Try to access web server using it-web.ph in End devices using Browser
---

## Author
**[ITArchitect111](https://github.com/ITArchitect111)**  
BS in Information Systems – Isabela, Philippines  
**TikTok**: [@it_ako123](https://www.tiktok.com/@it_ako123)

---

## License
This project is provided for educational purposes only.  
Feel free to fork or adapt it with proper credit.
