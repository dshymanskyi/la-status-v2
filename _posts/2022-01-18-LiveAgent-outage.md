---
layout: post
title: LiveAgent service outage
status: resolved
severity: outage
date: 2022-01-18 16:30
resolvedDate: 2022-01-18 16:40
clusters: [ustx]
services: [admin,calls,tickets,emails,chats]
incident_states:
- status: investigating
  content: "Outage on ustx based accounts"
- status: resolved
  content: "One of LB-DB nodes was unresponsive and couldn't connect to all DBs, it was for ~5 minutes when we spotted it and disabled traffic, there shouldn't be anything preventing accounts from proper work now."
---
