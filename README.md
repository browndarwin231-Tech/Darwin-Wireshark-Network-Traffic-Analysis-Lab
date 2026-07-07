# Darwin-Wireshark-Network-Traffic-Analysis-Lab
 A hands-on Wireshark lab demonstrating packet capture, network traffic analysis, DNS resolution, TLS/HTTPS inspection, TCP three-way handshake analysis, ICMPv6 traffic, protocol hierarchy, endpoint statistics, display filters, and packet-level troubleshooting.

---

## Repository Description

A hands-on Wireshark lab demonstrating packet capture, network traffic analysis, DNS resolution, TLS/HTTPS inspection, TCP three-way handshake analysis, ICMPv6 traffic, protocol hierarchy, endpoint statistics, display filters, and packet-level troubleshooting.

---

# Wireshark Network Traffic Analysis Lab

## Overview

This project demonstrates how to capture and analyze live network traffic using Wireshark. The lab covers essential networking concepts including DNS resolution, encrypted TLS/HTTPS communication, TCP connection establishment, ICMPv6 traffic, protocol hierarchy, endpoint analysis, packet inspection, and network troubleshooting.

This project showcases practical skills commonly used by Help Desk Technicians, Network Support Technicians, and SOC Tier 1 Analysts.

---

# Objectives

- Capture live network traffic
- Analyze DNS requests and responses
- Inspect encrypted TLS/HTTPS traffic
- Examine ICMPv6 network communication
- Understand the TCP three-way handshake
- Analyze packet headers
- Review protocol hierarchy
- Examine network conversations
- Identify communication endpoints
- Review capture statistics
- Use Wireshark display filters
- Inspect raw packet bytes

---

# Technologies Used

- Wireshark 4.6.6
- Npcap
- Windows 11
- TCP/IP
- IPv4
- IPv6
- DNS
- TLS/HTTPS
- Ethernet

---

# Skills Demonstrated

- Network Traffic Analysis
- Packet Capture
- DNS Analysis
- HTTPS/TLS Traffic Analysis
- TCP/IP Troubleshooting
- IPv4 & IPv6 Analysis
- Packet Inspection
- Protocol Analysis
- Network Diagnostics
- Display Filters
- Security Monitoring

---

# Screenshots

## 01-live-packet-capture.png

Displayed live network traffic captured from the active network interface, including TCP, UDP, and encrypted traffic.

![01-live-packet-capture.png](screenshots/01-live-packet-capture.png)

---

## 02-dns-traffic.png

Captured DNS queries and responses demonstrating domain name resolution, including A, AAAA, CNAME, and HTTPS DNS records.

![02-dns-traffic.png](screenshots/02-dns-traffic.png)

---

## 03-tls-traffic.png

Captured encrypted TLS 1.2 traffic over HTTPS (TCP port 443), demonstrating secure client-server communication.

![03-tls-traffic.png](screenshots/03-tls-traffic.png)

---

## 04-icmp-ping.png

Captured ICMPv6 network traffic, including Neighbor Solicitation, Neighbor Advertisement, Router Advertisement, and Multicast Listener messages.

![04-icmp-ping.png](screenshots/04-icmp-ping.png)

---

## 05-tcp-three-way-handshake.png

Captured TCP SYN and SYN/ACK packets demonstrating the TCP three-way handshake used to establish reliable network connections.

![05-tcp-three-way-handshake.png](screenshots/05-tcp-three-way-handshake.png)

---

## 06-packet-details.png

Expanded packet details displaying Frame, Ethernet II, IPv4/IPv6, and TCP headers for detailed packet analysis.

![06-packet-details.png](screenshots/06-packet-details.png)

---

## 07-protocol-hierarchy.png

Displayed protocol hierarchy statistics showing captured network protocols, packet counts, and protocol distribution.

![07-protocol-hierarchy.png](screenshots/07-protocol-hierarchy.png)

---

## 08-conversations.png

Displayed TCP conversation statistics showing communication sessions between local and remote hosts, including ports, packets, bytes, and connection duration.

![08-conversations.png](screenshots/08-conversations.png)

---

## 09-endpoints.png

Displayed endpoint statistics showing devices involved in the packet capture, including packet counts and transmitted/received bytes.

![09-endpoints.png](screenshots/09-endpoints.png)

---

## 10-capture-file-properties.png

Displayed capture file information, interface details, packet statistics, capture duration, and file metadata.

![10-capture-file-properties.png](screenshots/10-capture-file-properties.png)

---

## 11-display-filters.png

Demonstrated Wireshark display filters used to isolate specific protocols and packet types for targeted analysis.

![11-display-filters.png](screenshots/11-display-filters.png)

---

## 12-packet-bytes.png

Displayed the hexadecimal and ASCII representation of a captured packet for low-level packet inspection and analysis.

![12-packet-bytes.png](screenshots/12-packet-bytes.png)
