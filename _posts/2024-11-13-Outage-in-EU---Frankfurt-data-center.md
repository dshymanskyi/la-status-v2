---
layout: post
title: Outage in EU - Frankfurt data center
status: resolved
severity: outage
date: 2024-11-13 13:15 UTC
resolvedDate: 2024-11-13 13:30 UTC
clusters: [ec1]
services: [admin]
incident_states: 
- status: investigating
  content: 'We are currently experiencing an unexpected issue affecting our EU - Frankfurt data center. This outage has resulted in limited access to the agent panel, returning only "Bad gateway" or "Service unavailable" errors. Our infrastructure administrators are actively working to identify the root cause of the issue and restore full functionality as soon as possible. We understand the inconvenience this may cause and assure you that we are taking all necessary steps to resolve this incident promptly. We will continue to provide updates on our status page until the services are fully restored. We are very sorry for the temporary inconvenience & appreciate your patience and understanding.'
- status: resolved
  content: 'The issue has been caused by the recent migration of our legacy UK data center to the affected AWS EU data center, affecting only accounts on version 5.50.5.13. Our administrators have increased the resources of our servers to mitigate the problems and will continue observing the status of our data center.'
---
