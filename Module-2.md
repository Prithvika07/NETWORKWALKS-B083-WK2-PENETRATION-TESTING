# WEEK 2 | PROJECT MODULE 3

# FOOTPRINTING & RECONNAISSANCE ATTACKS WITH THEHARVESTER

## Description

theHarvester is a footprinting and Open-Source Intelligence (OSINT) tool used to gather publicly available information about a target organization. It can collect information such as email IDs, sub-domains, hosts, IP addresses, employee names, open ports, and banners from different public sources.

In this module, two reconnaissance tasks were performed using `example.com` as the target organization.

---

## Objective

The objective of this module is to understand how theHarvester can be used to gather publicly available information such as email IDs, sub-domains, and hosts during reconnaissance.

---

# Task 1 | Find Email IDs & Sub-Domains Using Baidu

### Objective

To find email IDs and sub-domains related to the target organization `example.com` using theHarvester in Kali Linux with **Baidu** as the source and a result limit of **1000**.

### Tool Used

**theHarvester**

### Target Organization

`example.com`

### Source

**Baidu**

### Result Limit

**1000**

### Command

theHarvester -d example.com -l 1000 -b baidu

### Procedure

1. Open Kali Linux.
2. Open the Terminal.
3. Run the theHarvester command.
4. Specify `example.com` as the target domain.
5. Select Baidu as the source.
6. Set the result limit to 1000.
7. Observe the information collected by the tool.

### Result

The theHarvester tool performed reconnaissance against `example.com` using Baidu.

The output showed:

- **IP Addresses Found:** None
- **Email Addresses Found:** None
- **People Found:** None
- **Hosts Found:** As displayed in the tool output.

The information identified was recorded from the theHarvester output.

---

# Task 2 | Find Email IDs & Sub-Domains Using All Sources

### Objective

To find email IDs and sub-domains related to the target organization `example.com` using theHarvester in Kali Linux with **all available sources** and a result limit of **50**.

### Tool Used

**theHarvester**

### Target Organization

`example.com`

### Sources

**All available sources**

### Result Limit

**50**

### Command

theHarvester -d example.com -l 50 -b all

### Procedure

1. Open Kali Linux.
2. Open the Terminal.
3. Run the theHarvester command.
4. Specify `example.com` as the target domain.
5. Select all available sources.
6. Set the result limit to 50.
7. Wait for the search to complete.
8. Observe the email IDs, sub-domains, hosts, and other information returned by the tool.

### Result

The theHarvester tool performed reconnaissance against `example.com` using all available sources with a result limit of 50.

The output was examined for publicly available information such as:

- Email addresses
- Sub-domains
- Hosts
- IP addresses
- Other reconnaissance information

---

# Conclusion

This module demonstrated the use of theHarvester for footprinting and reconnaissance against the target organization `example.com`.

Two tasks were completed. Task 1 used **Baidu** with a result limit of **1000**, while Task 2 used **all available sources** with a result limit of **50**.

The practical demonstrated how publicly available information can be gathered from multiple sources during the reconnaissance phase of a cybersecurity assessment.

> **Ethical Note:** Reconnaissance activities should only be performed against domains and systems for which proper authorization has been obtained.

---

# Screenshots

The screenshots for Task 1 and Task 2 are provided in this section.

## Task 1 Screenshot

![Task 1 - theHarvester Baidu](screenshots/17-theharvester-baidu.png)

## Task 2 Screenshot

![Task 2 - theHarvester All Sources](screenshots/18-theharvester-all.png)

> **Privacy Note:** Screenshots should contain only the information required for the practical demonstration. Sensitive organizational information, personal information, passwords, authentication credentials, API keys, private data, or other confidential information should not be revealed or published.
