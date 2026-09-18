# WEEK 2 | FOOTPRINTING & RECONNAISSANCE

## Project Overview

This project focuses on **Footprinting, Reconnaissance, and Network Scanning** using various cybersecurity tools available in Kali Linux.

The purpose of this project is to gain practical knowledge of the reconnaissance phase of a cybersecurity assessment. Different tools are used to collect and analyze publicly available information about an authorized target, including domain information, web technologies, DNS records, HTTP headers, security mechanisms, indexed information, email addresses, subdomains, hosts, ports, and services.

The project is divided into multiple modules, with each module focusing on a different reconnaissance or scanning technique.

---

## Project Objectives

The main objectives of this project are:

- To understand the concept of footprinting and reconnaissance.
- To gather publicly available information about an authorized target.
- To identify domain registration information.
- To fingerprint web technologies.
- To resolve domain names and identify IP addresses.
- To analyze HTTP response headers.
- To detect Web Application Firewalls.
- To enumerate DNS records.
- To understand Google Hacking Database (GHDB) techniques.
- To use theHarvester for email and subdomain discovery.
- To perform network scanning using Zenmap.
- To understand the importance of responsible and authorized security testing.

---

# Modules

## Module 1 | Footprinting & Reconnaissance with Multiple Kali Tools

This module focuses on using multiple Kali Linux tools for information gathering and reconnaissance.

### Tools Used

- WHOIS
- WhatWeb
- NSLookup
- cURL
- WAFW00F
- DNSRecon

[View Module 1 →](Module-1.md)

---

## Module 2 | Footprinting & Reconnaissance with GHDB

This module focuses on the **Google Hacking Database (GHDB)** and search engine operators.

The module demonstrates how search queries can be used to locate information that has already been indexed by search engines.

[View Module 2 →](Module-2.md)

---

## Module 3 | Footprinting & Reconnaissance with theHarvester

This module focuses on using **theHarvester** to gather publicly available information such as email addresses and subdomains from supported data sources.

The task includes using Baidu as the search source with a result limit of 1000.

[View Module 3 →](Module-3.md)

---

## Module 4 | Network Scanning with Zenmap

This module focuses on network scanning using **Zenmap**, the graphical interface for Nmap.

The scan is used to analyze authorized targets and identify information such as discovered hosts, open ports, and services.

[View Zenmap Module →](Zenmap.md)

---

# Tools Used

| Tool | Purpose |
|---|---|
| WHOIS | Domain registration information |
| WhatWeb | Web technology fingerprinting |
| NSLookup | DNS and IP address resolution |
| cURL | HTTP response header analysis |
| WAFW00F | Web Application Firewall detection |
| DNSRecon | DNS record enumeration |
| GHDB | Search engine reconnaissance |
| theHarvester | Email and subdomain discovery |
| Zenmap | Network scanning |

---

# Project Structure

```text
WEEK-2-RECONNAISSANCE/
│
├── README.md
│
├── Module-1.md
│
├── Module-2.md
│
├── Module-3.md
│
├── Zenmap.md
│
└── screenshots/
    ├── 01-whois.png
    ├── 02-whatweb.png
    ├── 03-nslookup.png
    ├── 04-curl.png
    ├── 05-wafw00f.png
    ├── 06-dnsrecon.png
    ├── 07-ghdb.png
    ├── 08-theharvester.png
    └── 09-zenmap.png
