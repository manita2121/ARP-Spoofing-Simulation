# ARP Spoofing & Man-in-the-Middle Attack Simulation

## Description
A cybersecurity research project demonstrating ARP Spoofing attacks 
and Man-in-the-Middle (MitM) techniques in a controlled virtual lab 
environment. The project includes two attack demonstrations and 
evaluates various mitigation strategies.

## Module
CC5009NI - Cyber Security in Computing  
Islington College | London Metropolitan University  
2024-25 Autumn Semester

## Team Members
- Manita Basnet (23047441)
- Krish Shrestha (23047364)
- Nirjal Pandey (23047518)
- Sulav Pathak (23047360)

## Attack Demonstrations

### Attack 1 - Bettercap (VMware Lab)
- Tools: Bettercap, Wireshark, Kali Linux
- Target: Windows 7 victim connecting to DVWA (Metasploitable2)
- Goal: Intercept unencrypted HTTP login credentials
- Result: Successfully captured valid login credentials

### Attack 2 - Ettercap (GNS3 Lab)
- Tools: Ettercap, Wireshark, GNS3
- Target: Windows 7 victim connecting to Router via Telnet
- Goal: Capture plaintext Telnet credentials
- Result: Successfully captured router login password

## Lab Environment
- Attacker: Kali Linux
- Victim: Windows 7
- Server: Metasploitable2 (DVWA)
- Network Simulator: GNS3
- Monitoring: Wireshark

## Mitigation Strategies Covered
- Static ARP Entries
- Dynamic ARP Inspection (DAI)
- VPNs and SSL/TLS Encryption
- Anti-ARP Tools (Snort, XArp, shARP)

## Tools Used
- Bettercap
- Ettercap
- Wireshark
- GNS3
- Kali Linux

## Disclaimer
This project was conducted strictly in a controlled virtual 
environment for educational purposes only under academic 
supervision. Do not replicate outside a lab environment.

## Authors
**Manita Basnet**  
BSc (Hons) Computer Networking & IT Security  
Islington College | London Metropolitan University
