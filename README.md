# Government Network Scenario Project

## Project Description
This project presents a comprehensive network scenario designed for a government setup, implemented using the eNSP (Enterprise Network Simulation Platform). The network encompasses a central cloud system, seven departmental routers, and various switches connecting departmental devices. The primary focus is on implementing key network technologies to ensure seamless connectivity and robust security across multiple government divisions.

## Table of Contents
- [Introduction](#introduction)
- [Background](#background)
- [Network Topology](#network-topology)
- [Implemented Technologies](#implemented-technologies)
  - [Telnet](#telnet)
  - [Access Control List (ACL)](#access-control-list-acl)
  - [Link Aggregation Protocol (LACP)](#link-aggregation-protocol-lacp)
  - [Static Route](#static-route)
  - [Dynamic Route - RIP](#dynamic-route---rip)
  - [Spanning Tree Protocol (STP)](#spanning-tree-protocol-stp)
  - [Variable Length Subnet Masking (VLSM)](#variable-length-subnet-masking-vlsm)
  - [Virtual Local Area Network (VLAN)](#virtual-local-area-network-vlan)
  - [Dynamic Host Configuration Protocol (DHCP)](#dynamic-host-configuration-protocol-dhcp)
  - [File Transfer Protocol (FTP)](#file-transfer-protocol-ftp)
- [Conclusion](#conclusion)

## Introduction
This project report details the implementation of a government network scenario using eNSP. The network includes a central cloud system, departmental routers, and switches connecting various devices. The following technologies were implemented to ensure optimal performance and security:
- Subnetting
- Telnet
- Security (ACL)
- Eth-Trunk
- Static Route
- RIP
- STP
- VLSM
- VLAN
- DHCP
- FTP

## Background
The Government Cloud network is designed to meet the operational needs of various governmental departments, including Defense, Finance, Home Affairs, Foreign Affairs, and Health. Each department is connected via dedicated routers, ensuring seamless connectivity and access to shared resources such as FTP servers and DNS services.

## Network Topology
The network topology includes:
- Central Router (R1)
- DHCP Server (R6)
- Departmental Routers for various divisions
- FTP Server (R5)
- Multiple switches connecting PCs in each division

## Implemented Technologies

### Telnet
Telnet provides a command-line interface for remote management of network devices. It was implemented to manage and configure the routers remotely.

### Access Control List (ACL)
ACLs enhance network security by controlling traffic and limiting access to network resources. ACLs were configured on routers to allow or deny specific IP addresses.

### Link Aggregation Protocol (LACP)
LACP combines multiple physical Ethernet links into a single logical link to increase bandwidth and provide redundancy. LACP was configured on switches to enhance performance and reliability.

### Static Route
Static routing involves manually configuring routes on routers. It is used in stable environments or for specific routing requirements.

### Dynamic Route - RIP (Routing Information Protocol)
RIP allows routers to exchange routing information dynamically. It uses hop count to determine the best path for forwarding packets.

### Spanning Tree Protocol (STP)
STP prevents loops in Ethernet networks by dynamically selecting the best path and blocking redundant links.

### Variable Length Subnet Masking (VLSM)
VLSM allows efficient IP address allocation by using subnet masks of varying lengths.

### Virtual Local Area Network (VLAN)
VLANs segment the network into different broadcast domains, enhancing security and reducing broadcast traffic.

### Dynamic Host Configuration Protocol (DHCP)
DHCP automates IP address assignment to devices on the network.

### File Transfer Protocol (FTP)
FTP facilitates the transfer of files between devices on the network.

## Conclusion
This project successfully demonstrates the implementation of a complex government network scenario using various network technologies. The detailed configuration and justification of each technology ensure a robust, secure, and efficient network infrastructure.
