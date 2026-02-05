---
layout: post
title: Overloaded servers in WS-EU data center
status: resolved
severity: outage
date: 2022-09-20 8:10 UTC
resolvedDate: 2022-09-20 13:00 UTC
clusters: [wseu]
services: [admin,calls,tickets,emails,chats]
incident_states:
- status: investigating
  content: "We are experiencing problems with overloading WS-EU data center. Accounts in this data center might have issues with loading LiveAgent panel. Our administrators are already investigating and solving the issue."
- status: update
  content: "Load was restored to nominal values and all LiveAgent accounts in the data center should work correctly again."
  date: 2022-09-20 8:45 UTC
- status: update
  content: "Returning issues were spotted, our administrators are insvestigating the problem."
  date: 2022-09-20 10:45 UTC
- status: resolved
  content: "Load on server is currently under control and customers should not observer any slowness right now."
---
