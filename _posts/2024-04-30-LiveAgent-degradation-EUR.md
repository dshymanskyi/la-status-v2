---
layout: post
title: LiveAgent service degradation
status: resolved
severity: degradation
date: 2024-04-30 08:52 UTC
resolvedDate: 2024-04-30 13:35 UTC
clusters: [ec1]
services: [admin]
incident_states:
- status: investigating
  content: 'Unexpected network performance problems in our new AWS data center. Customers may experience slowness affecting mainly filters and ticket grid.'
- status: update
  content: 'We were able to identify overloaded host and it is currently being removed and rebalanced. Right now, queue is dropping.'
  date: 2024-04-30 10:22 UTC
- status: update
  content: 'Some customers could be still facing issues with not seeing new tickets in the ticket grid, due to slow indexation of new conversations. Indexing queue is dropping slower than expected, should to be back to normal in aproximately 1 hour.'
  date: 2024-04-30 12:52 UTC
- status: resolved
  content: 'We are delighted to announce that the performance issues affecting our customers has been mitigated, and all affected services are now operating normally. Our team will continue monitoring the status of our servers. We apologize for any inconvenience this service degradation may have caused.'
  date: 2024-04-30 13:35 UTC
---
