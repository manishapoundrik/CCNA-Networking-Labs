# Project 1: VLAN and Inter-VLAN Routing

## Overview

Configured a small enterprise network using Cisco Packet Tracer to separate HR and IT departments into different VLANs and enable communication between them.

## Technologies

* Cisco Packet Tracer
* VLANs
* IEEE 802.1Q trunking
* Router-on-a-stick
* IPv4 addressing

## Network Design

| Department | VLAN ID | Network         | Default Gateway |
| ---------- | ------: | --------------- | --------------- |
| HR         |      10 | 192.168.10.0/24 | 192.168.10.1    |
| IT         |      20 | 192.168.20.0/24 | 192.168.20.1    |

## Configuration

* Created VLAN 10 (HR) and VLAN 20 (IT).
* Assigned switch access ports to the correct VLANs.
* Configured an 802.1Q trunk between the switch and router.
* Configured router subinterfaces for inter-VLAN routing.
* Verified connectivity using ping tests between different VLANs.

## Verification Results

* Ping from an HR PC to `192.168.20.11`: 0% packet loss.
* Ping from an HR PC to `192.168.20.12`: 25% packet loss in the displayed test; one request timed out.

## Files

* `Small_Enterprise_Network_Lab.pkt` — Packet Tracer topology and configuration.

## Learning Outcomes

Learned VLAN segmentation, trunk configuration, router subinterfaces, IP addressing, and inter-VLAN connectivity verification.
