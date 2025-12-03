# Cybersecurity Home Lab – Zubair Helal

This repository contains my personal cybersecurity home lab projects built in a Kali Linux virtual machine.  
Each project includes screenshots, summaries, and documentation of hands-on skills I practiced to learn real-world IT and security concepts.

# Project 1 – Network Verification (Kali Linux)

**Goal:** Confirm that the Kali Linux VM is properly connected to the network and able to communicate externally.

**What I did:**
- Identified network interfaces and IP configuration using `ip a`
- Verified ICMP connectivity with `ping 8.8.8.8`
- Verified DNS resolution with `ping google.com`
- Used `traceroute` to analyze routing paths
- Collected screenshots and documented findings

**Location:**  
`Project 1 - Network Verification/`

# Project 2 – Nmap Scanning (Reconnaissance)

**Goal:** Learn and apply network reconnaissance using Nmap on a legal test host.

**What I did:**
- Verified the Nmap installation with `nmap --version`
- Ran a basic scan on `scanme.nmap.org`
- Performed an aggressive scan using `nmap -A`
- Conducted OS fingerprinting with `nmap -O`
- Interpreted scan results and documented the process

**Location:**  
`Project 2 - Nmap Scanning/`

## 🛠 Tools Used
- Kali Linux (VMware Workstation)
- Nmap
- Linux command line (Bash)
- Basic network utilities (ip, ping, traceroute)

More lab projects will be added as I continue building my cybersecurity skills.
