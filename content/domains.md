---
title: domains
draft: false
tags:
  - programming
date: 2025-07-04
---
## how domains work
Domain names utilize Domain Name Systems which match up domain names to IP addresses. Every device connected to the internet has an IP address. When you enter a domain name in your browser, it sends a request to a server network, that acts like a giant phone book with info on all the domains. Then those servers look up the name servers and forward your request to those name servers.

Ok, so the real things you want to know when you're setting up your website (and what I mess up every time I set a new one up) is:
- What is an A record?
	- An A ("address") record is the most fundamental type of record. It indicates the IP address of a domain. So if you pull the DNS records of google.com, the A record will return an IP. A records only hold IPv4 addresses.
- What is a CNAME record?
	- A CNAME record is used instead of an A record and is used for aliases of another domain. All CNAME records have to point to a domain, and never an IP address.
	- I made a CNAME record for this site that's www.leveragedish.com. The www is a subdomain of leveragedish.com!