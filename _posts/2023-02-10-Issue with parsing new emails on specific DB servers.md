---
layout: post
title: Issue with parsing new emails on specific DB servers
status: Resolved
severity: degradation
date: 2023-02-10 14:00 UTC
resolvedDate: 2023-02-13 14:00 UTC
clusters: [ustx,de]
services: [tickets,emails]
incident_states: 
- status: investigating
  content: 'Multiple customers from two affected DB servers in our US - Texas and Frankfurt - Germany datacenter(s) are facing issues with new emails not being parsed and shown as empty. Our admins are investigating the issue.'
- status: update
  content: ''
  date: 
- status: resolved
  content: 'New tickets are being parsed correctly. Issue was caused by DB failover problem. We continue in deeper analysis of the rootcause to implement preventive actions as well as fix for affected tickets.'
---
