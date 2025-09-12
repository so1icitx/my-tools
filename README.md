# My Tools

## Overview
This repository showcases my personal projects for pentesting, network analysis, and programming exploration. Each tool is hosted in its own GitHub repository with details on purpose and features. We could add more stuff in future, like advanced features or new tools.

## Tools

### so1dump: Packet Sniffer
- **Repository**: [https://github.com/so1icitx/packet_sniffer](https://github.com/so1icitx/packet_sniffer)
- **Purpose**: Captures and analyzes network packets (TCP, UDP, ICMP) on a specified interface.
- **Features**: 
  - Parses packet details like source/destination IPs, ports, and flags.
  - Supports output to JSON (clean format), CSV, or text files.
  - Optional hex dump of packet data.
  - AbuseIPDB lookup for destination IP reputation (requires API key).
  - Quiet mode to suppress terminal output.
-

### so1map: Port Scanner
- **Repository**: [https://github.com/so1icitx/so1map](https://github.com/so1icitx/so1map)
- **Purpose**: Scans single IPs or subnets to identify open ports.
- **Features**: 
  - Scans specified port ranges with multi-threading for speed.
  - Supports single IP (e.g., `192.168.1.1`) or subnet (e.g., `192.168.1.0/24`) scanning.
  - Outputs to JSON (clean format), CSV, or text files.
  - Quiet mode to save results without terminal output.


### ARP Spoofer
- **Repository**: [https://github.com/so1icitx/so1icitx-arp-spoofer](https://github.com/so1icitx/so1icitx-arp-spoofer)
- **Purpose**: Performs ARP spoofing for man-in-the-middle (MITM) attacks on local networks.
- **Features**: Redirects traffic by spoofing ARP tables to intercept packets.


### Hash Identifier
- **Repository**: [https://github.com/so1icitx/so1-hash-identifier](https://github.com/so1icitx/so1-hash-identifier)
- **Purpose**: Identifies hash types (e.g., MD5, SHA1) based on string patterns.
- **Features**: Analyzes hash formats and suggests possible algorithms.


### Network Scanner
- **Repository**: [https://github.com/so1icitx/so1ic-network-scanner](https://github.com/so1icitx/so1ic-network-scanner)
- **Purpose**: Discovers live hosts, open ports, and services on a network.
- **Features**: Performs host discovery and port scanning.


### MAC Spoofer
- **Repository**: [https://github.com/so1icitx/macso1i](https://github.com/so1icitx/macso1i)
- **Purpose**: Changes a network interface’s MAC address.
- **Features**: Temporarily modifies MAC addresses for anonymity or bypassing filters.


## Learning Journey
- **Repository**: [https://github.com/so1icitx/so1icitx-programming-journey](https://github.com/so1icitx/so1icitx-programming-journey)
- **Purpose**: Tracks my programming progress through projects, exercises, and notes.
- **Features**: Includes code samples and milestones across various languages.
- **Use Case**: Serves as a reference and inspiration for learning to code.

## Disclaimer
Use these tools responsibly and only on systems or networks you have permission to test. Unauthorized use may violate laws or terms of service.
