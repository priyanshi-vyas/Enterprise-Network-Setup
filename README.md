# NetGuard Financial Solutions
NetGuard Financial Solutions is a Design of an Enterprise Bank Network along with its simulation is implemented using cisco packet tracer

## Bank network requirements
- Bank consists of 3 branches and 1 main branch.
- Main branch has 4 departments which are segregated by creating different VLANS.
- Bank consists of a server room present on cloud which consists of a web server, an FTP and a DNS server.
- The whole bank network is connected by routers.


NetGuard Financial Solutions
This repository contains a comprehensive network topology for a bank's enterprise network, created using Cisco Packet Tracer. The design is structured to ensure optimal performance, security, and scalability for various departments or branch offices within the bank.

Key Features of the Network Design:

1.VLAN Segmentation:
  The network is segmented into multiple VLANs (Virtual Local Area Networks), each representing a different branch or department. This logical separation improves security 
  and reduces broadcast traffic within the network.

2.Inter-VLAN Routing:
  A centralized router is configured to perform inter-VLAN routing (Router-on-a-Stick), enabling communication between devices in different VLANs while maintaining logical 
  separation.
  This setup ensures that departments can securely communicate across the network.

3.Branch Office Integration:
  Multiple branches or departments are connected over a WAN (Wide Area Network), with each branch having its own subnet. The central router handles routing between these 
  branches to facilitate seamless communication.

4.Subnetting and IP Addressing:
  A structured IP addressing scheme is used for each VLAN and branch, making it easy to manage and scale the network. Subnetting is implemented to efficiently utilize the IP 
  space and ensure secure communication between departments.

5.Switches and Devices:
  Each VLAN has its own switch that connects multiple end devices (such as PCs, printers, and servers). These switches are responsible for internal communication within each 
  VLAN.
  The devices are configured with specific IP addresses to match their respective VLANs, following the subnetting scheme.

6.Scalability:
  The design is highly scalable, allowing the addition of new branches or departments with minimal reconfiguration.


Technologies Used:

  Cisco Packet Tracer: Network design and simulation
  Router-on-a-Stick: To enable inter-VLAN routing using a single router
  VLAN Configuration: To segment the network into logical departments or branches
  IP Subnetting: Efficient IP address allocation for each department
  Switches: Layer 2 devices used for connecting end devices within VLANs
  Routers: For handling routing between different VLANs and branches

Applications:

This network design is suitable for a large enterprise, such as a bank, where multiple departments or branches need to be securely segmented while allowing controlled communication across the network. The architecture ensures high availability, performance, and security.

File Structure:

NetGuard Financial Solutions.pkt: Cisco Packet Tracer project file with the complete network topology and configuration.
README.md: Documentation for the project, including a detailed description of the network design and its features.
Future Enhancements:
Firewall Integration: Adding firewalls to improve network security.
DHCP Server Configuration: Implementing DHCP servers for dynamic IP address assignment to devices.
Wireless Network Setup: Integrating wireless access points (WAP) for employees and guests.
