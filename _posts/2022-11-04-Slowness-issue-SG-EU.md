---
layout: post
title: Slowness issues in SG and EU datacenters
status: resolved
severity: degradation
date: 2022-11-04 04:00 UTC
resolvedDate: 2022-11-05 23:00 UTC
clusters: [sg,wseu,de]
services: [admin,calls,tickets]
incident_states:
- status: investigating
  content: "Multiple customers, mainly from our SG datacenter, but also some bigger customers from our EUR datacenters are facing slowness issues, specially on the chats. In case there are multiple chats running at the same time, it's taking more time than usual for chat pick up and also customer’s texts are not showing real time. Our admins are investigating issue as they can see higher utilization on our servers that is most likely behing this issues, they are trying to identify the rootcause."
- status: update
  content: "Our admins in cooperation with our development team have identified the rootcause in our latest release and are preparing a patch with the fix."
  date: 2022-11-05 13:00 UTC
- status: resolved
  content: "Patch with the fix have been deployed and customers should no longer experience slowness issues."
---
