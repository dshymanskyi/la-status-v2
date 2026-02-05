---
layout: post
title: Connectivity degradation related to problems on AWS side
status: resolved
severity: degradation
date: 2025-10-20 15:00 UTC
resolvedDate: 2025-10-20 22:01 UTC
clusters: [ue1]
services: [admin,tickets]
incident_states: 
- status: investigating
  content: 'We are again experiencing an unexpected connectivity degradation affecting our U.S. data center. This degradation has resulted in limited access to the panel or tickets. Our technical team is actively working to identify the root cause of the issue and restore full functionality as soon as possible. We understand the inconvenience this may cause and assure you that we are taking all necessary steps to resolve this incident promptly. We will continue to provide updates on our status page once there is any new info and the services are fully restored. We appreciate your patience and understanding during this time.'
- status: update
  content: 'The issues are related to data center wide network problems on AWS side, globally affecting various companies, banks, apps, etc. around the world. Amazon is investigating increased error rates and latencies for multiple AWS services in the US-EAST-1 Region. Their team is actively working to both mitigate the issue and understand root cause. More details can be found on Amazon Service Health page https://health.aws.amazon.com/health/status. We will provide an update if we have additional information to share.'
  date: 2025-10-20 15:05 UTC
- status: resolved
  content: 'According to the Amazon Service Health page,  all AWS services returned to normal operations'
---
