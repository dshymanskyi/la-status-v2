---
layout: post
title: Call center connectivity issues in UK datacenter
status: resolved
severity: degradation
date: 2022-11-03 10:36 UTC
resolvedDate: 2022-11-03 16:36 UTC
clusters: [uk,wseu]
services: [calls]
incident_states:
- status: investigating
  content: "Due to issues in our UK Linode datacenter (see: https://status.linode.com/incidents/sk329t1y1mx6), agents from UK (and some EUR customers) are facing connectvity problems and lower quality during incoming and outgoing calls. Our admins are in contact with our provider Linode to get the solution asap."
- status: update
  content: "Linode team have identified the issue affecting connectivity in their London data center. They are working quickly to implement a fix, and will provide an update as soon as the solution is in place."
  date: 2022-11-03 12:36 UTC
- status: resolved
  content: "We received confirmation from our provider Linode that thay have been able to correct the issues affecting connectivity in the UK (London) data center"
---

More details: [Linode incident](https://status.linode.com/incidents/sk329t1y1mx6)
