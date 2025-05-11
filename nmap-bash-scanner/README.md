# Automated Network Reconnaissance using Nmap and Bash

## Overview
This project is focused on automating network scanning tasks using Nmap and Bash scripting on Linux. The goal is to help beginners understand how cybersecurity professionals gather information about networks, identify vulnerabilities, and build a basic automated tool.

## Objective
- Understand basic Nmap usage for scanning networks.
- Learn to write Bash scripts to automate scanning operations.
- Create a tool that:
  - Accepts a target IP range or domain
  - Performs ping, port, and OS detection scans
  - Saves results in organized files

## Folder Structure
nmap-bash-scanner/
├── README.md  
├── scan.sh  
├── results/  
│   └── internal_server_scan.txt  
└── LICENSE (optional)

## Tools Used
- Nmap
- Bash
- GitHub

## How It Works
1. Run `scan.sh` and input a target IP/domain
2. Script performs:
   - Ping scan
   - Port scan
   - OS detection
3. All results are saved in the `results/` folder
