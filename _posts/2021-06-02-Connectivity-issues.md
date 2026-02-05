---
layout: post
title: Network problems affecting accounts on DE and US datacenters
status: Resolved
status: investigating
severity: outage
date: 2021-06-02 14:00
resolvedDate: 2021-06-02 16:40 UTC
clusters: [ustx,usnj,sg,uk,de,wseu]
services: [admin,calls,tickets,emails]
incident_states:
- status: investigating
  content: "We are investigating recent network issues. We will share more details soon"
- status: update
  content: "We are facing issues with the DNS affecting all our Datacenters. Our admins are intensively working on a solution"
  date: 2021-06-02 15:00
- status: resolved
  content: It was a flooding attack on our DNS server - a remote attacker was flooding our server with queries in order to leave no capacity for legitimate user queries.
---
