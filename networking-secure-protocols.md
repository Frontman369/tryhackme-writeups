# Networking Secure Protocols - TryHackMe Writeup

## Overview
This room focused on how network communication is secured using protocols such as TLS, SSH, and VPNs. It explored the risks of plaintext communication and how secure protocols protect confidentiality, integrity, and authenticity across networks.

---

## Objectives
- Understanding the purpose of SSL/TLS  
- Learning how plaintext protocols are secured  
- Exploring how SSH replaces insecure remote access methods  
- Understanding how VPNs secure communication across networks  

---

## Protocols & Concepts Covered
- SSL/TLS  
- HTTPS  
- SMTPS  
- POP3S  
- IMAPS  
- SSH  
- VPNs  
- Packet analysis with Wireshark  

---

## Key Concepts

### TLS (Transport Layer Security)
TLS secures network communication by protecting:
- Confidentiality  
- Integrity  
- Authenticity  

Protocols such as HTTP, SMTP, POP3, and IMAP become secure through TLS, resulting in:
- HTTPS  
- SMTPS  
- POP3S  
- IMAPS  

Without encryption, attackers monitoring network traffic could read or modify sensitive data.

---

### SSH (Secure Shell)
SSH replaced insecure protocols like TELNET by providing encrypted remote access to systems.

It can also:
- transfer files securely  
- create encrypted tunnels  
- protect otherwise insecure traffic  

---

### VPN (Virtual Private Network)
VPNs create secure communication channels over untrusted networks, commonly used to securely connect remote users or company branches.

---

## Practical Exercise
The room concluded with a hands-on challenge involving packet analysis using Wireshark.

I analyzed a captured network traffic file and identified login credentials transmitted within the packets, demonstrating the risks of insecure or improperly protected communication.

---

## Challenges Faced
- Understanding how encryption protects network communication  
- Differentiating the roles of TLS, SSH, and VPNs  
- Interpreting packet data during analysis  

---

## Key Takeaways
- Plaintext protocols expose sensitive data to interception  
- TLS adds confidentiality, integrity, and authenticity to communication  
- SSH provides secure remote system access  
- VPNs protect traffic across untrusted networks  
- Packet analysis reveals how exposed network traffic can become a security risk  

---

## Reflection
This room strengthened my understanding of how modern network communication is secured. It connected previous networking concepts with practical security implementations and demonstrated why encrypted communication is essential in real-world environments.

It also marked the conclusion of a four-room networking series, reinforcing the importance of strong networking fundamentals in cybersecurity.
