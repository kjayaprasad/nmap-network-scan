# nmap-network-scan
an nmap scan on my local machine

# Nmap Network Scan

This project contains the results of a TCP SYN scan on the local network `192.168.1.0/24`.

## Contents

- Nmap Scan Results (`.nmap`, `.xml`, `.gnmap`)
- Open Port Summary
- Security Risk Analysis
- (Optional) Wireshark Packet Capture

# Open Ports Summary

## Host: 192.168.1.10
- Port 22: SSH - Open
- Port 80: HTTP - Open

## Host: 192.168.1.15
- Port 443: HTTPS - Open

# Security Analysis

## 192.168.1.10 - SSH (Port 22)
- Risk: Brute-force vulnerability
- Recommendation: Use key-based authentication

## 192.168.1.15 - NetBIOS (Port 139)
- Risk: Possible SMB enumeration
- Recommendation: Disable if unused
