# Cybersecurity Home Lab

## Overview

This project is my personal cybersecurity home lab built for learning and practising cybersecurity concepts in a safe and authorised environment.

The lab uses virtual machines to create an isolated network where I can practise networking, security tools, vulnerability assessment, Python, documentation, and Git/GitHub.

---

## Lab Environment

### Kali Linux

Kali Linux is used as the security workstation.

It provides tools for:

* Network scanning
* Security testing
* Network analysis
* Vulnerability assessment
* Security research

### Metasploitable 2

Metasploitable 2 is an intentionally vulnerable virtual machine used as the authorised practice target.

All testing is performed only inside this home lab.

### Oracle VirtualBox

Oracle VirtualBox is used to run the virtual machines.

---

## Network Setup

The Kali Linux and Metasploitable 2 virtual machines communicate through a:

**Host-only Adapter**

This creates a private virtual network for the lab.

```text
Kali Linux
    |
    | Host-only Network
    |
Metasploitable 2
```

The host-only network allows the two virtual machines to communicate with each other without exposing the vulnerable Metasploitable 2 machine directly to the public internet.

Before starting security testing, connectivity was verified by testing communication between Kali Linux and Metasploitable 2.

---

## Project Objectives

The main objectives of this home lab are to:

* Build a safe cybersecurity practice environment
* Understand basic virtual networking
* Practise network reconnaissance
* Identify open ports and running services
* Perform basic vulnerability assessment
* Analyse network traffic
* Practise web application security testing
* Use Python for cybersecurity-related tasks
* Document security testing activities
* Use Git and GitHub to manage and showcase the project

---

## Tools Used

* Kali Linux
* Metasploitable 2
* Oracle VirtualBox
* Python
* Git
* GitHub
* Nmap
* Wireshark
* Burp Suite

---

## Lab Activities

The home lab provides a controlled environment for practising different cybersecurity activities.

### 1. Network Discovery

Nmap is used to discover the Metasploitable 2 machine and identify services running on the target.

This helps me understand:

* IP addresses
* Open ports
* Network services
* Service versions
* Basic network reconnaissance

### 2. Vulnerability Assessment

The intentionally vulnerable Metasploitable 2 machine provides a safe target for learning how vulnerabilities can be identified.

The assessment focuses on understanding:

* Exposed services
* Potential vulnerabilities
* Security risks
* Evidence collected during testing
* How vulnerabilities should be documented

### 3. Network Traffic Analysis

Wireshark is used to capture and inspect network traffic between the virtual machines.

This helps me learn how to identify and understand:

* Network protocols
* Source and destination addresses
* TCP and UDP traffic
* DNS traffic
* HTTP traffic
* Network communication patterns

### 4. Web Application Testing

Burp Suite is used to practise basic web application security testing against applications running inside the authorised lab environment.

This allows me to learn about:

* HTTP requests and responses
* Headers
* Parameters
* Cookies
* Web application traffic
* Basic security testing techniques

### 5. Python

Python is used for relevant cybersecurity tasks and automation.

The goal is to develop practical programming skills that can be applied to security tasks such as analysing information, processing results, and automating repetitive activities.

---

## Testing and Validation

Before performing security testing, the lab environment was checked to make sure the virtual machines could communicate correctly.

The following checks were performed:

* Kali Linux successfully started
* Metasploitable 2 successfully started
* Both virtual machines were connected to the Host-only network
* Kali Linux could communicate with Metasploitable 2
* Network connectivity was tested using ping
* Nmap was used to verify that the target was reachable
* Security tools were tested against the authorised practice target

These checks confirmed that the lab was ready for cybersecurity testing.

---

## Troubleshooting and Solutions

Building the lab involved several problems. These were documented and solved step by step.

### 1. Kali Linux Networking Problem

The Kali Linux virtual machine initially had a networking configuration problem.

The VirtualBox network settings were checked and the Host-only Adapter was configured correctly.

After correcting the configuration, Kali Linux was able to communicate with Metasploitable 2.

### 2. Virtual Machine Connectivity

Connectivity between the two virtual machines was tested using their assigned IP addresses.

Once both machines were connected to the same Host-only network, communication between Kali Linux and Metasploitable 2 was successfully established.

### 3. Tool Configuration

Some tools required configuration and testing before they could be used effectively.

Each tool was tested individually to understand its purpose and confirm that it could communicate with the authorised lab environment.

---

## Skills Demonstrated

This project demonstrates practical experience with:

* Linux
* Virtual machines
* Virtual networking
* Network reconnaissance
* Nmap
* Vulnerability assessment
* Wireshark
* Burp Suite
* Python
* Git
* GitHub
* Technical documentation
* Troubleshooting
* Cybersecurity lab design

---

## What I Learned

Building this home lab helped me understand how cybersecurity tools work in a practical environment rather than only learning the theory.

I learned how to create an isolated virtual network, connect security and target machines, troubleshoot networking problems, perform basic reconnaissance, analyse network traffic, and document cybersecurity activities.

The project also helped me become more comfortable working with Kali Linux, VirtualBox, command-line tools, Python, Git, and GitHub.

---

## Future Improvements

I plan to expand the home lab as my cybersecurity skills develop.

Future improvements may include:

* Adding additional virtual machines
* Creating a small simulated business network
* Adding Windows and Linux endpoints
* Building Active Directory practice environments
* Adding a SIEM such as Microsoft Sentinel
* Creating security monitoring and detection exercises
* Automating additional tasks with Python
* Creating more vulnerability assessment reports
* Adding incident-response scenarios

---

## Project Structure

The project is organised to keep the lab configuration, documentation, scripts, and reports e
