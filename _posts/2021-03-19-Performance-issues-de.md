---
layout: post
title: Performance issues on DE-DC
status: investigating
severity: outage
date: 2021-03-19 11:20
resolvedDate: 2021-03-19 12:55
clusters: [de]
services: [admin,calls,tickets,emails]
incident_states:
- status: investigating
  content: "We are investigating an outage in our DE datacenter."
  date: 2021-03-19 11:20
- status: update
  content: "Issues are caused by the DDoS attack on LBs in Linode DE."
  date: 2021-03-19 12:20
- status: resolved
  content: "The number of active connections has been falling steadily due to the deployed mitigation and I we're back to normal."
  date: 2021-03-19 12:55
---
