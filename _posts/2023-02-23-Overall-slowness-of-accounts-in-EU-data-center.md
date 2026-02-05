---
layout: post
title: Overall slowness of accounts in EU data center
status: resolved
severity: degradation
date: 2023-02-23 07:49 UTC
resolvedDate: 2023-02-23 08:39 UTC
clusters: [wseu]
services: [admin,calls,tickets,emails]
incident_states: 
- status: investigating
  content: "Customers with LiveAgent accounts in the EU data center might experience overall slowness of their panel due to potential issues with our infrastructure. Our administrators are already investigating the issue, we will keep this post updated."
- status: resolved
  content: "Our team have found problematic parent servers and disabled traffic to servers on them. The issue was caused by a Hypervisor limit which was exhausted during DDoS attack, which caused some unpredictable behavior on network layer. Our hardware provider  enabled monitoring that allows us to know when a similar problem will be happening sooner in the future. Everything should work back again as usual. We will keep monitoring the status of our servers."
---
