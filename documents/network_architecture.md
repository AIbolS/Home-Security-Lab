# Network Architecture

## Overview
Three-tier security architecture with segmentation.

## Segments
1. **WAN** - Internet-facing (10.0.2.0/24)
2. **LAN** - Internal trusted network (192.168.10.0/24)
3. **DMZ** - Semi-trusted server zone (192.168.20.0/24)

## IP Addresses
- pfSense LAN: 192.168.10.1
- pfSense DMZ: 192.168.20.1
- Kali Linux: 192.168.10.100
- Metasploitable: 192.168.20.10
