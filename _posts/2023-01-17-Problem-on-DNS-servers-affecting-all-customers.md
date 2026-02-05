---
layout: post
title: Problem on DNS servers affecting all customers
status: investigating
severity: outage
date: 2023-01-17 01:20 UTC
resolvedDate: 2023-01-17 02:16 UTC
clusters: [ustx,usnj,sg,uk,de,wseu]
services: [admin,calls,tickets,emails]
incident_states: 
- status: investigating
  content: 'The LiveAgent panel for all our customers, as well as our main website, is unavailable due to a problem with the DNS server. Our admins are investigating the issue and trying to resolve it asap.'
- status: update
  content: ''
  date: 
- status: resolved
  content: 'Issue with the DNS servers was resolved. Root cause seems to be a DDOS attack on our DNS servers. We are monitoring the situation.'
---
