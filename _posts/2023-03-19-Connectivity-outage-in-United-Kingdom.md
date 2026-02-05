---
layout: post
title: Connectivity outage in United Kingdom
status: resolved
severity: outage
date: 2023-03-19 15:06 UTC
resolvedDate: 2023-03-19 17:16 UTC
clusters: [uk]
services: [admin,calls,tickets,emails]
incident_states: 
- status: investigating
  content: 'Multiple customers, mainly from our United Kingdom datacenter(s) are facing connectivity outage, especially on the following services: Admin, Calls, Tickets and Emails. Our admins are investigating the issue as they can see higher utilization on our servers.'
- status: update
  content: 'UK cluster is down due to an infrastructure issues in Linode. Linode has problems only using some specific route, therefore, only certain providers are unable to access LiveAgent panel.'
  date: 2023-03-19 16:10 UTC
- status: resolved
  content: 'The connection to agent panel has been re-established.'
---
