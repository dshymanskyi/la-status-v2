---
layout: post
title: LiveAgent service outage
status: resolved
severity: outage
date: 2022-05-27 11:14
resolvedDate: 2022-05-27 11:48
clusters: [wseu]
services: [admin,calls,tickets,emails,chats]
incident_states:
- status: investigating
  content: "Unexpected outage affecting account on our EUR-WS datacenter, customers getting error 500"
- status: resolved
  content: "Problem with error 500 should be fixed and service is availabe again. Issue was caused by incorrectly switched traffic during upgrade in our EUR Ws datacenter."
---
