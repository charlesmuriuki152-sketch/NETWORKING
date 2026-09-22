# Networking Fundamentals and Cybersecurity

A practical learning repository covering networking fundamentals, Linux networking commands, hands-on labs, Packet Tracer exercises, and cybersecurity-focused networking projects.

## Purpose

This repository documents my progress in networking as part of my **Cybersecurity Mission 2028**. It combines theoretical concepts with practical Linux-based investigations and future network simulation exercises.

## Learning Objectives

- Understand the purpose of computer networks and communication protocols
- Explain the difference between IP addresses and MAC addresses
- Identify and inspect Linux network interfaces
- Read routing tables and identify default gateways
- Test local and remote network connectivity
- Understand ports, sockets, and listening services
- Connect networking concepts to cybersecurity operations
- Build a foundation for traffic analysis, incident response, and network security

## Repository Contents

| Resource | Description |
| --- | --- |
| [Networking Basics](./Networking-Basics) | Detailed notes covering networks, IP and MAC addresses, interfaces, gateways, loopback, routing, ports, and listening services |
| [Networking Fundamentals Lab](./NETWORKING%20FUNDAMENTALS%20LAB) | Practical Linux lab documenting commands, observations, troubleshooting, and cybersecurity connections |

## Topics Covered

- Computer networks
- IPv4 and IPv6 addressing
- MAC addresses
- Network interfaces
- Loopback communication
- Routing tables
- Default gateways
- Network ports
- TCP and UDP sockets
- Listening services
- Basic connectivity testing
- Network visibility and attack-surface analysis

## Linux Commands Practiced

```bash
ip addr
ip link
ip route
ping -c 4 127.0.0.1
ping -c 4 <destination>
ss -tuln
ss -tulpn
```

## Cybersecurity Relevance

Networking knowledge supports:

- Security monitoring
- Network reconnaissance in authorized environments
- Traffic analysis
- Incident response
- Firewall configuration
- Attack-surface analysis
- Vulnerability assessment
- Network segmentation
- Security engineering

A key principle from this stage is:

> Understand what is connected, how it communicates, what it exposes, and why.

## Progress

- [x] Networking fundamentals
- [x] Linux interface inspection
- [x] IP and MAC address identification
- [x] Routing and default-gateway inspection
- [x] Loopback connectivity testing
- [x] Basic network connectivity testing
- [x] Listening-port inspection
- [ ] Packet Tracer exercises
- [ ] Wireshark traffic analysis
- [ ] Network security projects

## Environment and Tools

- Kali Linux
- Linux terminal
- Cisco Packet Tracer
- `iproute2` networking utilities
- `ping`
- `ss`

## Documentation Standards

Each practical exercise aims to record:

1. The objective
2. The environment and tools used
3. Commands executed
4. Observed results
5. Interpretation of the results
6. Troubleshooting lessons
7. Cybersecurity relevance
8. Skills developed

## Learning Path

This repository provides a foundation for future work in:

- Wireshark and traffic analysis
- SOC and blue-team operations
- Incident response
- Ethical hacking
- Vulnerability management
- Cloud security
- Security engineering

## License

This project is licensed under the [MIT License](./LICENSE).
