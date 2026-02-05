---
layout: post
title: The attack on the crucial part of LiveAgent's infrastructure
status: resolved
severity: outage
date: 05-03-2020 01:40
resolvedDate: 05-03-2020 17:00
clusters: [ustx,usnj,uk,de,sg,wseu]
services: [admin,calls,tickets,emails]
incident_states:
- status: investigating
  content: "Technical problems reported and investigation started."
- status: update
  content: "Issue had been identified and work on resolution started."
  date: 05-03-2020 05:36
- status: services restoring
  content: "Patch had been applied. We started with restoring the services."
  date: 05-03-2020 07:48
- status: update
  content: "US-TX Data Center had been restored."
  date: 05-03-2020 10:41 
- status: update
  content: "Most of our Data Centers had been restored."
  date: 05-03-2020 16:00
- status: resolved
  content: "all remaining Data Centers had been restored."
---
At approximately 03:00 am (UTC +2), a remote attacker managed to exploit a critical vulnerability in a 3rd party system that is a crucial part of LiveAgent's infrastructure. There’s no indication that the customer’s data was exploited, tampered with, or leaked. According to our insights, the attacker’s goal was to mine cryptocurrencies. [Find more details here.](https://www.liveagent.com/blog/2020-05-security-incident/)

---
