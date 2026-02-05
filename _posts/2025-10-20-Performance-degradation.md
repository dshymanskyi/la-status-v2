---
layout: post
title: Performance degradation related to problems on AWS side
status: resolved
severity: degradation
date: 2025-10-20 07:19 UTC
resolvedDate: 2025-10-20 10:35 UTC
clusters: [ue1,ec1]
services: [admin,emails,tickets]
incident_states: 
- status: investigating
  content: 'We are currently experiencing an unexpected degradation affecting our U.S. and Europe data centers, excluding the Asia & Pacific data center. This degradation has resulted in various temporary problems as delayed email sending or incorrect ticket filters, and is affecting also other background jobs. The issues are related to problems on AWS side, globally affecting various companies, banks, apps, etc. around the world. Amazon is investigating increased error rates and latencies for multiple AWS services in the US-EAST-1 Region. Their team is actively working to both mitigate the issue and understand root cause. More details can be found on Amazon Service Health page https://health.aws.amazon.com/health/status. We will provide an update if we have additional information to share.'
- status: update
  content: 'Amazon has applied initial mitigations and we are observing early signs of recovery for impacted services.'
  date: 
- status: resolved
  content: 'According to the Amazon Service Health page, the underlying DNS issue has been completely resolved, and the majority of operations are now functioning normally. Please note, some requests may experience throttling as Amazon works toward reaching full resolution. Rest assured, our team will continue to monitor the status of our services to guarantee performance and stability.'
---
