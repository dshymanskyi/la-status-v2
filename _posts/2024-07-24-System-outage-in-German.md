---
layout: post
title: System outage in our EUR linode datacenter
status: investigating
severity: outage
date: 2024-07-24 14:05 UTC
resolvedDate: 2024-07-24 14:30 UTC
clusters: [de]
services: [admin,calls,tickets,emails]
incident_states: 
- status: investigating
  content: 'We are currently experiencing an unexpected service outage affecting our European Linode data center in Germany. This outage has resulted in limited access to the following services: Admin, Calls, Tickets and Emails. Our technical team is actively working to identify the root cause of the issue and restore full functionality ASAP. We understand the inconvenience this may cause and assure you that we are taking all necessary steps to resolve this incident promptly. We will continue to provide updates on our status page and will notify you once the services are fully restored. We appreciate your patience and understanding during this time.'
- status: update
  content: 'Health-check failed on both LBs simultaneously. Situatiuon will be analyzed in cooperatio with our provider Linode to prevent similar cases in the future.'
  date: 2024-07-24 14:30 UTC
- status: resolved
  content: 'The situation is stabilised, the outage lasted from 16:05-16:30 CEST.'
---
