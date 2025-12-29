# Network Scanning & Information Gathering using Nmap

## Overview
This project demonstrates network scanning and information gathering using Nmap,
an industry-standard cybersecurity tool widely used in ethical hacking.

The objective of this project is to identify live hosts, open ports,
running services, operating system details, and network paths in a safe
and ethical manner.

## Tools Used
- Nmap 7.98
- Zenmap GUI
- Windows OS

## Scan Command Used
nmap -A scanme.nmap.org

## Target
- scanme.nmap.org (Official Nmap test server)

## Results Summary
- Host Status: Live
- Open Ports: 22 (SSH), 80 (HTTP), 9929, 31337
- Services Detected: OpenSSH, Apache HTTP Server
- OS Detected: Linux (Kernel 4.x – 5.x)
- Traceroute analysis performed

## Screenshots
- ![Scan Start](IMG-20251229-WA0010)
- ![Scan Running](IMG-20251229-WA0012)
- ![Scan Results](IMG-20251229-WA0011)
- ![Scan Results](IMG-20251229-WA0012)
- ![Scan Results](IMG-20251229-WA0009)

## Video Demo
- [Watch Demo](VID-20251229-WA0013)

## Ethical Consideration
All scans were performed on authorized targets only for educational purposes.
