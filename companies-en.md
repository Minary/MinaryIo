---
layout: page
title: Companies
lang: en
permalink: /companies/
---

To improve your security as a company, here are a few tips that can also help you defend against tools like Minary:

  - Minary attacks target systems using broadcast protocols. At the moment only ARP is used, but in future DHCP and NDP for IPv6 will be supported as well. These attack vectors can be eliminatedon (professional) switches.

  - There is no valid reason not to use HTTPS anymore. [Let's Encrypt](https://letsencrypt.org/) offers free certificates that can be rapidly installed.
  
  - Force the use of encryption using **permanent redirects** from HTTP to HTTPS.
  
  - **Use HTTPS on all systems**. One system may link to another and unencrypted systems are vulnerable to manipulations. The smaller the attack surface for intruders, the smaller the risk for users.
  
  - **Use HSTS** so that users are forced to use encryption when communicating with your systems. Use _includeSubDomains_ as well as _preload_.
  
