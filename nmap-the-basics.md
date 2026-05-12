# Nmap: The Basics - TryHackMe Writeup

## Overview
This room introduced the fundamentals of Nmap, one of the most widely used network scanning and reconnaissance tools in cybersecurity. The focus was on discovering active hosts, identifying open ports and services, understanding scan techniques, and controlling how scan data is collected and displayed.

---

## Objectives
Throughout this room, I learned how to:
- Identify active systems within a network  
- Detect open ports and exposed services  
- Understand the differences between common scan types  
- Gather version information from running services  
- Adjust scan speed and timing behavior  
- Save and format scan results for analysis  

---

## Tools & Concepts Used
- Nmap  
- Host discovery  
- Port scanning  
- Service enumeration  
- Version detection  
- Scan timing control  
- Output formatting  

---

## Key Concepts

### Host Discovery
I learned how Nmap identifies which systems are online and reachable within a network before deeper scanning begins.

---

### Port Scanning
The room demonstrated how open ports reveal listening services and potential entry points on a target system.

Understanding which ports are exposed is a critical step in reconnaissance and attack surface analysis.

---

### Service & Version Detection
I explored how Nmap can gather additional details about running services, including version information that may help identify outdated or vulnerable software.

---

### Scan Timing & Performance
The room introduced timing controls that influence how aggressively or slowly scans are performed.

This highlighted the balance between:
- speed  
- accuracy  
- stealth  

during network reconnaissance.

---

### Output & Reporting
I learned how Nmap scan results can be displayed and saved in different formats, making documentation and later analysis easier.

---

## Important Observation
One of the key lessons from this room was understanding the difference between running Nmap with normal user privileges versus elevated privileges.

Certain scan techniques require the ability to craft raw packets, which typically needs administrative or root-level access. Without elevated privileges, some advanced scan capabilities become unavailable or behave differently.

---

## Challenges Faced
- Understanding the purpose of different scan types  
- Interpreting scan results and service information  
- Learning how timing settings affect scans  

---

## Key Takeaways
- Nmap is a foundational tool for reconnaissance and enumeration  
- Open ports reveal valuable information about exposed services  
- Version detection helps identify potential weaknesses  
- Scan timing can impact speed, visibility, and reliability  
- Elevated privileges unlock more advanced scanning capabilities  

---

## Reflection
This room provided a strong introduction to practical network reconnaissance using Nmap. It demonstrated how much information can be gathered from systems through careful scanning and enumeration.

It also reinforced the importance of understanding not only how to run scans, but why different scan techniques and configurations matter during security assessments.

While this room covered the fundamentals, it also made it clear how extensive and powerful Nmap becomes at more advanced levels.
