---
layout: post
title: Performance issues on TX-DC
status: resolved
severity: degradation
date: 2021-03-19 7:47
resolvedDate: 2021-03-19 8:58
clusters: [ustx]
services: [admin,calls,tickets,emails]
incident_states:
- status: investigating
  content: "Performace of one of US datacenters is degraded."
  date: 2021-03-19 7:47
- status: update
  content: "Scheduled Network Maintenance - US-Central (Dallas)"
  date: 2021-03-19 7:53
- status: resolved
  content: "The maintenance is over, all services work normally again"
  date: 2021-03-19 8:58
---

We found out the performance issue is connected with a scheduled maintenance in US DC datacenter:

[Linode status page](https://status.linode.com/incidents/bw33mgv3dzxg)
