---
layout: post
title: Performance issues on DE-DC
status: resolved
severity: outage
date: 2021-03-24 12:30
resolvedDate: 2021-03-24 16:00
clusters: [de]
services: [admin,calls,tickets,emails]
incident_states:
- status: investigating
  content: "We are investigating an outage in our DE datacenter."
  date: 2021-03-24 12:30
- status: update
  content: "Issues are caused by the DDoS attack on LBs in Linode DE."
  date: 2021-03-24 12:40
- status: update
  content: "We managed to get the situation under control around 14:00, but we're still dealing with some accounts. There's a couple of IP addresses that are evading our rate limiting, so the investigation continues."
  date: 2021-03-24 14:20
- status: resolved
  content: "We rate limit each IP address to 300 concurrent connections and we'll probably deploy that permanently on all our LBs in order to prevent from the same situation in the future. We've also banned a whole range belonging to a Polish ISP. We consider this issue as resolved."
  date: 2021-03-24 16:00
---
