---
layout: post
title: Issues in US-Newark data canter
status: resolved
severity: outage
date: 2021-09-22 16:45 
resolvedDate: 2021-09-22 21:30 CEST 
clusters: [usnj]
services: [admin,calls,tickets,emails]
incident_states:
- status: investigating
  content: "We are experiencing issues in one of our data centers on our provider's side, customers might be receiving error 'Failed to subscribe/unsubscribe channels - request timed out. Empty response received from server' and not be able to work freely in their panels. Our team is monitoring the issue."
  date:  2021-9-22 16:26 PM GTM+2
- status: update
  content: "Linode just confirmed issues on their side, waiting for further details."
  date:  2021-9-22 18:26 PM GTM+2
- status: resolved
  content: "The data center performance in US-NJ cluster is stabilized at the moment, no new incidents detected."
- date: 2021-09-22 21:30 CEST
---
