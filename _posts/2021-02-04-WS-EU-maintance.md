---
layout: post
title: Unexpected maintenance on WS-EU
status: resolved  
severity: degradation
date: 2021-02-04 12:00
resolvedDate: 2021-02-04 13:00
clusters: [wseu]
services: [emails]
incident_states:
- status: update
  content: "unexpected maintenance"
  date: 2021-02-04 12:00 
- status: resolved
  content: "In the last half an hour, there was a window of ~15 minutes, when LA accounts in WS-EU might had been unable to receive emails due to problems with TLS configuration."
---
