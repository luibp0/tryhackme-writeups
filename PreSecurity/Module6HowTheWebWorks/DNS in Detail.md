# DNS in Detail

## Overview

This room introduces the **Domain Name System (DNS)** and explains how domain names are translated into IP addresses so devices can locate and communicate with services across networks.

It covers the DNS hierarchy, common DNS record types, the DNS resolution process, and the different DNS servers involved when resolving a domain name.

## Objectives

* Understand the purpose of DNS.
* Learn how domain names are structured.
* Understand the DNS hierarchy.
* Learn about common DNS record types.
* Understand how DNS queries are resolved.
* Learn the roles of different DNS servers.
* Understand DNS caching and TTL.

## Skills Learned

* DNS fundamentals
* Domain name structure
* DNS hierarchy
* DNS record identification
* DNS resolution process
* DNS server roles
* DNS caching concepts
* Basic DNS troubleshooting

## Tools Used

* TryHackMe Learning Platform
* Web Browser
* `nslookup`

## Key Takeaways

* DNS translates human-readable domain names into IP addresses that computers can use.
* Domain names are organized into a hierarchical structure.
* Top-Level Domains (TLDs) include extensions such as `.com`, `.org`, and `.net`.
* DNS uses different record types, including **A, AAAA, CNAME, MX, and TXT** records.
* Recursive DNS servers help clients resolve domain names by communicating with other DNS servers.
* Root DNS servers direct queries toward the appropriate TLD servers.
* TLD servers help locate the authoritative DNS server responsible for a domain.
* Authoritative DNS servers contain DNS records for their domains.
* **TTL (Time To Live)** determines how long a DNS record can remain cached.
* Tools such as `nslookup` can be used to query DNS information.

## Reflection

This room helped me understand how DNS works behind the scenes when accessing websites and other network services.

I learned how DNS queries move through recursive, root, TLD, and authoritative DNS servers before the correct information is returned. I also gained a better understanding of DNS records, caching, TTL, and how tools such as `nslookup` can be used to inspect DNS information.

These concepts provide an important foundation for networking and cybersecurity because DNS plays a major role in how devices locate and communicate with services across the Internet.

---

> **Note:** Personal learning notes only. No flags, answers, or complete walkthroughs are included.
