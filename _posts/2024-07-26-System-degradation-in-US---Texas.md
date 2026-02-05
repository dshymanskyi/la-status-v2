---
layout: post
title: System degradation in US - Texas
status: investigating
severity: degradation
date: 2024-07-26 13:30 UTC
resolvedDate: 2024-07-26 22:30 UTC
clusters: [ustx]
services: [tickets]
incident_states: 
- status: investigating
  content: 'We are currently experiencing an unexpected service degradation affecting US - Texas data center. This degradation has resulted in limited access to the following services: Tickets.
  Visibility of tickets in the LiveAgent panel might be affected and some customers might not see all their tickets. We apologize for this temporary impact and assure you that all your tickets should become visible again. Our technical team is actively working to identify the root cause of the issue and restore full functionality ASAP. We understand the inconvenience this may cause and assure you that we are taking all necessary steps to resolve this incident promptly. We will continue to provide updates on our status page and will notify you once the services are fully restored. We appreciate your patience and understanding during this time.'
- status: update
  content: 'The problem occured when switching Elasticsearch (ES) from Linode to AWS, afecting 2 shards out of 50, so aprox. 3% of tickets were not visible for some customers. Now one of the two primary shards was restored, reducing the number of impacted tickets to only 1.7% of tickets. Our admins are still working on fix of the the second primary shard and then they will reindex any missing changes.'
  date: 2024-07-26 17:30 UTC
- status: resolved
  content: 'We are pleased to announce that the issue affecting the visibility of a small portion of tickets for some of our customers has been successfully resolved. All affected services have been fully restored. We successfully recovered all primary shards, ensuring all tickets are now visible. Right now we are waiting only for replicas to be completed - these are needed for redundancy, but all tickets should be visible already.'
---
