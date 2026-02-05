---
layout: post
title: Overall panel slowness in multiple data centers
status: resolved
severity: degradation
date: 2023-11-15 08:05 UTC
resolvedDate: 2023-11-15 15:15 UTC
clusters: [de,wseu,sg]
services: [admin]
incident_states: 
- status: investigating
  content: "We are currently experiencing an unexpected degradation affecting multiple data centers. This degradation has resulted in the overall slowness of the LiveAgent panel. Our infrastructure administrators are actively working to identify the root cause of the issue and restore full functionality as soon as possible. We understand the inconvenience this may cause and assure you that we are taking all necessary steps to resolve this incident promptly. We will continue to provide updates on our status page and will notify you once the issues are fully fixed. We appreciate your patience and understanding during this time."
- status: update
  content: "Our administrators have identified the cause of the overloads and our developers continue mitigating the issue. Our administrators will add more computing power to our machines as needed to ensure as best performance as possible."
  date: 2023-11-15 12:00 UTC
- status: resolved
  content: "The situation with performance & slowness issues is currently stabilized and customers should observe an improvement and faster loading in the panel already. The issue that caused the problems although  needs to be fixed by our developers directly within our application, as after deeper investigation it turned out that the issue is not on the server side. For now, no further critical degradation should be experienced, our infrastructure administrators will continue monitoring the status of our machines and will resize our machines after peak hours to prevent further issues in the future until the issue is fully fixed on all sides. Please accept our sincere apologies for the caused inconvenience and thank you for your patience and understanding."
---
