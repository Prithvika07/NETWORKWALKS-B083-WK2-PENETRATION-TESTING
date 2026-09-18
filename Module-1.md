# WEEK 2 | PROJECT MODULE 1

# FOOTPRINTING & RECONNAISSANCE ATTACKS WITH MULTIPLE KALI TOOLS

## Description

This module focuses on performing footprinting and reconnaissance using multiple tools available in Kali Linux. The practical activities were performed on the NetworkWalks target to gather publicly available information about the domain and its web infrastructure.

The following Kali Linux tools were used in this module:

* **WHOIS** – Domain registration information
* **WhatWeb** – Web technology fingerprinting
* **NSLookup** – Domain and IP address resolution
* **cURL** – HTTP response header analysis
* **WAFW00F** – Web Application Firewall detection
* **DNSRecon** – DNS record enumeration

The purpose of this module is to understand how different reconnaissance tools can be used to collect and analyze information during a cybersecurity assessment.

## Objective

The objective of this module is to perform footprinting and reconnaissance using multiple Kali Linux tools against the NetworkWalks target.

The following tasks were performed:

* **Task 1:** WHOIS – Domain registration details
* **Task 2:** WhatWeb – Web technology fingerprinting
* **Task 3:** NSLookup – Domain-to-IP resolution
* **Task 4:** cURL – HTTP response header analysis
* **Task 5:** WAFW00F – Web Application Firewall detection
* **Task 6:** DNSRecon – DNS record enumeration

---

# Task 1 | WHOIS

## Objective

To find the domain registration details of the NetworkWalks target.

## Tool Used

**WHOIS**

## Command Used

```bash
whois networkwalks.com
```

## Description

WHOIS is a command-line tool used to retrieve publicly available information about a registered domain. The information may include registrar details, domain status, registration dates, and nameservers.

## Procedure

1. Open the Kali Linux terminal.
2. Run the WHOIS command with the NetworkWalks domain.
3. Observe the domain registration information displayed in the terminal.

## Screenshot

<img width="1920" height="922" alt="week2 p1 output4" src="https://github.com/user-attachments/assets/f36340be-75e6-421c-9863-13b5a224a0ea" />


## Result

The WHOIS command was successfully executed and the available domain registration information was displayed.

---

# Task 2 | WhatWeb

## Objective

To identify and fingerprint the web technologies used by the NetworkWalks website.

## Tool Used

**WhatWeb**

## Command Used

```bash
whatweb networkwalks.com
```

## Description

WhatWeb is a web technology fingerprinting tool used to identify technologies and components associated with a website. It can identify web servers, frameworks, content management systems, JavaScript libraries, and other technologies.

## Procedure

1. Open the Kali Linux terminal.
2. Run the WhatWeb command with the NetworkWalks domain.
3. Observe the technologies identified by the tool.

## Screenshot

<img width="1857" height="340" alt="Screenshot 2026-09-18 162146" src="https://github.com/user-attachments/assets/bbfec503-76f9-4c63-8d0e-6463d7fdbb32" />


## Result

WhatWeb successfully analyzed the target website and displayed the web technologies identified.

---

# Task 3 | NSLookup

## Objective

To resolve the NetworkWalks domain name to its corresponding IP address.

## Tool Used

**NSLookup**

## Command Used

```bash
nslookup networkwalks.com
```

## Description

NSLookup is a DNS query tool used to resolve domain names into IP addresses and obtain DNS-related information.

## Procedure

1. Open the Kali Linux terminal.
2. Run the NSLookup command with the NetworkWalks domain.
3. Observe the DNS response and IP address information.

## Screenshot

<img width="1858" height="375" alt="Screenshot 2026-09-18 162252" src="https://github.com/user-attachments/assets/44f7ae8a-d185-498a-80fa-91e5f614831b" />


## Result

The NetworkWalks domain was successfully resolved and the available IP address information was displayed.

---

# Task 4 | cURL

## Objective

To examine the HTTP response headers returned by the NetworkWalks website.

## Tool Used

**cURL**

## Command Used

```bash
curl -I https://networkwalks.com
```

## Description

The `curl -I` command retrieves the HTTP response headers from a web server without downloading the complete webpage. These headers may provide information about the server response, content type, redirects, caching, and security-related configurations.

## Procedure

1. Open the Kali Linux terminal.
2. Run the cURL command with the NetworkWalks website.
3. Examine the HTTP response headers displayed in the terminal.

## Screenshot

<img width="1851" height="228" alt="Screenshot 2026-09-18 162443" src="https://github.com/user-attachments/assets/6f57e220-20a1-41c3-b748-fdc1ed5d091c" />


## Result

The HTTP response headers returned by the NetworkWalks website were successfully retrieved and examined.

---

# Task 5 | WAFW00F

## Objective

To detect whether a Web Application Firewall (WAF) is protecting the NetworkWalks website.

## Tool Used

**WAFW00F**

## Command Used

```bash
wafw00f https://networkwalks.com
```

## Description

WAFW00F is a tool used to identify and fingerprint Web Application Firewalls. It analyzes responses from a web application and attempts to determine whether a recognizable WAF is present.

## Procedure

1. Open the Kali Linux terminal.
2. Run the WAFW00F command with the NetworkWalks website.
3. Observe the WAF detection result.

## Screenshot

<img width="1135" height="255" alt="Screenshot 2026-09-18 162730" src="https://github.com/user-attachments/assets/d9fd1245-7723-479d-ac59-b7a1a4596665" />


## Result

WAFW00F analyzed the NetworkWalks website and displayed the result of its WAF detection process.

---

# Task 6 | DNSRecon

## Objective

To enumerate DNS records associated with the NetworkWalks domain.

## Tool Used

**DNSRecon**

## Command Used

```bash
dnsrecon -d networkwalks.com
```

## Description

DNSRecon is a DNS enumeration tool used to gather information about the DNS infrastructure of a domain and identify available DNS records.

## Procedure

1. Open the Kali Linux terminal.
2. Run the DNSRecon command with the NetworkWalks domain.
3. Observe the DNS records discovered by the tool.

## Screenshot

<img width="1097" height="403" alt="Screenshot 2026-09-18 162634" src="https://github.com/user-attachments/assets/4706b763-60ec-4b4b-b336-782df5e7ebc4" />

## Result

DNSRecon successfully performed DNS enumeration and displayed the DNS records discovered for the NetworkWalks domain.

---

# Conclusion

This module demonstrated the use of multiple Kali Linux tools for footprinting and reconnaissance.

The tools were used to gather different types of information:

| Tool     | Purpose                            |
| -------- | ---------------------------------- |
| WHOIS    | Domain registration information    |
| WhatWeb  | Web technology fingerprinting      |
| NSLookup | IP address and DNS information     |
| cURL     | HTTP response header analysis      |
| WAFW00F  | Web Application Firewall detection |
| DNSRecon | DNS record enumeration             |

The practical activities helped develop an understanding of how different reconnaissance tools can be used to collect and analyze publicly available information during a cybersecurity assessment.

> **Ethical Note:** All reconnaissance activities should be performed only against systems for which proper authorization has been obtained.
