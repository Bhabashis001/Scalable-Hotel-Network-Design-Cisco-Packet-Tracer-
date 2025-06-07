Problem Statement: Scalable Hotel Management Network Design
Objective:
Create a secure, scalable, and functional network for a hotel using Cisco Packet Tracer. The
network should ensure departmental isolation, controlled data sharing, and efficient resource
management while being capable of accommodating future growth. This network will
simulate real-life hotel operations and address key IT challenges.

Scenario:
A large hotel with multiple departments—Reception, Finance, Restaurant, and Sales—
requires a robust network design to handle its daily operations securely. Each department has
distinct requirements and handles critical functions as follows:

1.Reception: Manages guest check-ins, reservations, and communication with the
finance department for billing. Requires direct communication with the finance
department while being isolated from others.

2.Finance: Handles sensitive financial data such as payroll, invoices, and transactions.
No department except reception should have access to this data.

3.Restaurant: Manages food orders, inventory, and guest room service. Operates
independently from finance but shares occasional data with sales for promotions.

4.Sales: Focuses on marketing campaigns, online bookings, and promotions. Can
communicate with the restaurant but not with finance.

The network must be designed to:
• Ensure secure inter-departmental communication using VLANs, ACLs, and Inter-
VLAN Routing.
• Enable centralized control for efficient management and troubleshooting.
• Provide redundancy to maintain operations during device failures.
• Ensure scalability for future expansion, including adding new departments or
branches.

Additional Features:
1. Centralized Server:
o Deploy a centralized server for storing shared files like promotional materials,
daily sales reports, and customer feedback forms.
o Host the server in a separate VLAN (e.g., VLAN 50, 192.168.50.0/24) with
access controlled via ACLs.
2. Guest Wi-Fi Network:
o Configure a guest VLAN (VLAN 60) to provide internet-only access for hotel
guests.
o Isolate this VLAN from all internal networks.

Deliverables:
1. Network Topology Diagram:
o Include all devices, VLANs, IP addresses, and interconnections.
2. Configuration Files:
o Provide switch and router configurations for VLANs, routing, DHCP, and
ACLs.
3. Test Results:
o Screenshots or logs showing successful implementation of VLANs, inter-
VLAN routing, STP redundancy, and ACL enforcement.
