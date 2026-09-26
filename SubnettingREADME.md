Subnetting Fundamentals
Overview
Subnetting is the process of dividing an IP network into smaller logical networks called subnets.

It is an important networking concept and a foundational cybersecurity skill because cybersecurity engineers need to understand how systems are organized and communicate across networks.

1. What Is Subnetting?
Subnetting divides a larger IP network into smaller networks.

For example:

192.168.10.0/24

can be divided into smaller subnets.

Each subnet has:

Network address
Usable host range
Broadcast address
Number of available host addresses
2. CIDR Prefix
CIDR stands for Classless Inter-Domain Routing.

The number after / indicates how many bits of an IPv4 address are used for the network portion.

For example:

192.168.10.0/24

This means:

Network bits = 24
Host bits = 32 - 24
Host bits = 8

Total addresses:

2^8 = 256

Usable host addresses:

256 - 2 = 254

The two reserved addresses are the network address and broadcast address.

3. Important Subnetting Terms
Network Address
The first address in a subnet. It identifies the subnet itself.

Broadcast Address
The last address in a subnet. It is used to communicate with all hosts within that subnet.

First Usable Address
The address immediately after the network address.

Last Usable Address
The address immediately before the broadcast address.

Usable Hosts
The number of addresses available for hosts within a subnet.

For most traditional IPv4 subnets:

Usable hosts = Total addresses - 2

4. Host Bits and Network Bits
An IPv4 address contains 32 bits.

The CIDR prefix determines how many bits belong to the network.

For example:

/20

means:

Network bits = 20
Host bits = 12

Therefore:

2^12 = 4096 total addresses

and:

4096 - 2 = 4094 usable hosts

5. Why Subnetting Matters in Cybersecurity
Subnetting helps cybersecurity engineers understand network structure and boundaries.

It can be used when working with:

Network segmentation
Firewall rules
Access-control policies
Security zones
Network monitoring
Traffic analysis
Incident response
Vulnerability assessment
Network reconnaissance
For example, an organization may separate servers, employees, security monitoring systems, and other devices into different subnets.

This can help control which systems are allowed to communicate with each other.

6. Security Scenario
Consider an organization with separate network segments:

Web Servers
Database Servers
Employee Systems
Security Monitoring
Subnetting can be used to place these systems into different network ranges.

Security controls such as firewalls and access-control rules can then be configured according to the organization's network design.

7. Cybersecurity Connection
Understanding subnetting is important for cybersecurity because security engineers need to understand where systems exist within a network.

Subnetting knowledge supports:

Network security
Firewall configuration
SOC monitoring
Traffic analysis
Incident response
Vulnerability management
Penetration testing
Network reconnaissance
Security architecture
A cybersecurity engineer should be able to identify the network, host range, and broadcast address from an IPv4 address and CIDR prefix.

Key Takeaway
Subnetting divides networks into smaller logical networks.

The most important skills are being able to determine:

Network Address
Broadcast Address
First Usable Address
Last Usable Address
Number of Usable Hosts
These skills form an important foundation for practical networking and cybersecurity engineering.
