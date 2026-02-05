---
layout: post
title: Connectivity degradation in Western Europe
status: resolved
severity: degradation
date: 2023-07-10 08:05 UTC
resolvedDate: 2023-07-10 17:00 UTC
clusters: [wseu]
services: [admin,calls,tickets,emails]
incident_states: 
- status: investigating
  content: 'We are currently experiencing an unexpected connectivity degradation affecting our Western Europe data center(s). This degradation has resulted in limited access to the following services: Admin, Calls, Tickets and Emails. Our technical team is actively working to identify the root cause of the issue and restore full functionality ASAP. We understand the inconvenience this may cause and assure you that we are taking all necessary steps to resolve this incident promptly. We will continue to provide updates on our status page and will notify you once the services are fully restored. We appreciate your patience and understanding during this time.'
- status: update
  content: 'The issue is caused by multiple international fiber outages in Europe. More details can be found on https://ecogent.cogentco.com/network-status'
  date: 2023-07-10 08:45 UTC
- status: update
  content: 'We switched traffic from Cogent to back up provider. This workaround resolved the issue with the connectivity of our customers. Please note this is a temporary fix and we are waiting for a final resolution from 
  the Cogent side. We will keep you updated.'
  date: 2023-07-10 10:15 UTC
- status: resolved
  content: 'Fiber issues located in the area of Eastern Germany (Emstek-Bramsche) were restored and we also performed emergency works to get additional capacity. Due to that, services should be working fine, without any packet loss or extra latency.'
---
