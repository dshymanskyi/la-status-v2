---
layout: post
title: DNS problems affecting UK, DE and EU datacenters
status: Resolved
severity: outage
date: 2021-06-17 10:50
resolvedDate: 2021-06-17 11:50
clusters: [uk,de,wseu]
services: [admin,calls,tickets,emails]
incident_states:
- status: investigating
  content: "We are investigating DNS issues caused by an attack on our DNS servers."
- status: resolved
  content: "DNS issues were resolved. Data remains unaffected."
  date: 2021-06-17 11:50
---
We've prepared protection to prevent this type of attack for the future and added a new layer of security. Even during the attack we successfully made mitigation in order for any of our customers' accounts not being affected.
