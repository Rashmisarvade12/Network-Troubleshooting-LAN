# Network Troubleshooting & LAN Configuration Lab

## Overview

A Cisco Packet Tracer networking lab demonstrating LAN configuration,
VLANs, trunking, DHCP, inter-VLAN routing and basic network troubleshooting.

## Tools & Technologies

- Cisco Packet Tracer
- CCNA Networking Concepts
- IPv4 Addressing
- Subnetting
- VLANs
- Trunking
- DHCP
- Router-on-a-Stick
- Ping
- Traceroute
- Network Troubleshooting

## Network Topology

The lab consists of:

- 1 Cisco Router
- 2 Cisco Switches
- 4 PCs

## VLAN Configuration

| VLAN | Name | Devices |
|------|------|---------|
| 10 | USERS | PC0, PC2 |
| 20 | ADMIN | PC1, PC3 |

## IP Addressing

| Device | IP Address | Default Gateway |
|--------|------------|-----------------|
| PC0 | 192.168.10.2 | 192.168.10.1 |
| PC1 | 192.168.20.2 | 192.168.20.1 |
| PC2 | 192.168.10.3 | 192.168.10.1 |
| PC3 | 192.168.20.3 | 192.168.20.1 |

## Configuration

- Configured VLAN 10 and VLAN 20.
- Configured access ports for end devices.
- Configured trunk links between network devices.
- Configured DHCP pools for automatic IP assignment.
- Configured router subinterfaces for inter-VLAN routing.
- Configured default gateways for both VLANs.

## Network Testing

Connectivity was tested using:

- Ping
- Traceroute
- IP configuration verification

A VLAN configuration issue was also simulated and resolved as part of the troubleshooting exercise.

## Project Outcome

Successfully established connectivity between devices within the same VLAN
and communication between different VLANs through the router.

## Files

- `Network_Troubleshooting_LAN.pkt` — Cisco Packet Tracer project file
- `screenshots/` — Configuration and testing screenshots