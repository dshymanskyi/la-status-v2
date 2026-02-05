---
layout: post
title: Tickets reindexing degradation
status: resolved
severity: degradation
date: 2024-05-08 05:30 UTC
resolvedDate: 2024-05-08 10:05 UTC
clusters: [ec1]
services: [admin]
incident_states:
- status: investigating
  content: 'After the recent migration of LiveAgent acccounts to new servers performed earlier today, customers may experience degradated tickets reindexing performance affecting mainly ticket filters.'
- status: update
  content: 'The task to re-check and index all tickets to resolve the issues with ticket filters has been scheduled for all accounts. Our team will keep monitoring the status of the queue.'
  date: 2024-04-30 8:20 UTC
- status: resolved
  content: 'Majority of accounts shall have tickets correctly reindexed. Our developers will keep monitoring the status and will manually fix any isolated cases if needed. If you still experience issues with ticket filters, please do not hesitate to contact our live chat support.'
---
