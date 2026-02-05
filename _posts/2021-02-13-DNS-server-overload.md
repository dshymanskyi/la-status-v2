---
layout: post
title: Performance issues on WS-EU
status: resolved 
severity: degradation
date: 2021-02-13 7:30
resolvedDate: 2021-02-13 15:00
clusters: [wseu]
services: [admin]
incident_states:
- status: investigating
  content: "Performance issues observed on WS-EU. One of the DNS servers is overloaded. Customers may notice that their panel is unreachable for several minutes."
  date: 2021-02-13 09:00
- status: update
  content: "The overloaded DNS server has been under a DOS attack. Attackers´ IP addresses are constantly banned. We are still monitoring the issue. DNS server is calming down."
  date: 2021-02-13 12:00
- status: resolved
  content: "There should not be any further performance issues due to the recent DOS attacks, it was already eliminated."
  date: 2021-02-13 15:00
---
