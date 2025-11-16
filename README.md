# IT-Networking-Office-LAN

This project demonstrates a complete network topology setup using:
- **3 Router**
- **1 Firewall**
- **5 Switches**
- **1 Cloud**
- **1 Modem**
- **4 Servers**
- **End Devices**

The use Configuration use was **Dynamic Host Configuration Protocol (DHCP)**, **Virtual Local Area Network(VLAN)**, **Open Shortest Path First(OSPF)** , **Hot STanbdy Routing Protocol(HSRP)**,and **Spanning Tree Protocol(STP)**, **File Transfer Protocol(FTP), **Hypertext Transfer Protocol Secure(HTTPS)**, **Simple Mail Transfer Protocol(SMTP)**, **Post Office Protocol(POP)**,"Port Address Translation(PAT)**, **Access List**, **Secret Shell(SSH)**, and **Domain Name System(DNS)**. Designed and simulated using **Cisco Packet Tracer**, this setup is ideal for Implementing the past projects in real life topology or infrastructure.

---

## Project Objectives
- Design and Implement an Enterprise Network Topology to develop a complete and scalable network infrastructure integrating routers, switches, firewall, servers, and end devices that emulate a real-world enterprise environment.
- Implement Dynamic IP Addressing using DHCP to automate IP address assignment across all network segments for LAN, minimizing manual configuration and IP conflicts.
- Segment Network using VLANs To separate departments (Accounting, HR, and Marketing) into logical networks, improving security, manageability, and performance.
- Optimize Routing through OSPF to establish efficient dynamic routing between routers, ensuring fast convergence and optimal path selection.
- Enhance Network Security and Remote Access using SSH and ACLs to secure administrative access through encrypted remote sessions (SSH) and restrict unauthorized traffic via Access Control Lists (ACL).
- Set ACLs per VLAN where, Accounting can only access accounting.itserver.ph, HR can only access hr.itserver.ph, and Marketing can only access marketing.itserver.ph and each HTTP per vlan cant access outside.
- Set up Outside Server for extension using itserver.ph as Extension for Internal DNS servers.
- Implement Network Services for Enterprise Operations to deploy essential services such as:
- Enable FTP with roles per VLAN Department where users can share and download files base on their roles in FTP Server.
- Email (SMTP/POP) for communication.
- Apply PAT for Internet Connectivity to allow multiple internal devices to access external networks securely using Port Address Translation.
- Evaluate Network Performance and Reliability to test and verify connectivity, redundancy, routing efficiency, and service availability under simulated conditions.
---

## Repository Contents

# Configurations/
- **Internet.txt**
- **Firewall.txt**
- **Network.txt**
- **RouterServer.txt**
- **Access.txt**
- **Accounting.txt**
- **HR.txt**
- **Marketing.txt**

# IT Networking Source File/
- **IT Network 6(IT Security for LAN).pkt**

# Overview
![Topology](Overview/IT_Network_6.png)

# README.md

## Tools Used
- **Cisco Packet Tracer** – for simulation and design
- **Text Editor** – for writing and reviewing CLI configs

---

## How to Use
1. Open the `IT Network 6(IT Security for LAN).pkt` file using **Cisco Packet Tracer**.
2. Check Network devices if they have DHCP, VLANs, and ACLS.
3. Ping HTTP Service per VLAN.
4. Try to ping outside IP Address in VLAN Department.
5. Try to config `show ip nat trans` in Router enable mode.
6. Open the dedicated DNS of each VLAN in Browser using their domain name or IP Adddress.
7. Try to open FTP in cmd of end devices in VLAN Department by putting `ftp 172.111.65.3` and put the dedicated username and password.
---

## Author
**[ITArchitect111](https://github.com/ITArchitect111)**  
BS in Information Systems – Isabela, Philippines  
**TikTok**: [@it_ako123](https://www.tiktok.com/@it_ako123)

---

## License
This project is provided for educational purposes only.  
Feel free to fork or adapt it with proper credit.
