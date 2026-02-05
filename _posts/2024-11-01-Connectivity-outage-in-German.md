---
layout: post
title: Connectivity outage in Linode DE data center
status: investigating
severity: outage
date: 2024-11-01 08:30 UTC
resolvedDate: 2024-11-01 10:40 UTC
clusters: [de]
services: [admin,calls,tickets,emails]
incident_states: 
- status: investigating
  content: 'We are currently experiencing an unexpected connectivity outage affecting Elasticsearch clusters in Linode DE data center. This outage has resulted in limited access to the following services: Admin, Calls, Tickets and Emails. Our technical team is actively working to identify the root cause of the issue and restore full functionality ASAP. We understand the inconvenience this may cause and assure you that we are taking all necessary steps to resolve this incident promptly. We will continue to provide updates on our status page and will notify you once the services are fully restored. We appreciate your patience and understanding during this time.'
- status: update
  content: ''
  date: 
- status: resolved
  content: 'We are pleased to inform you that the recent connectivity outage has been successfully resolved, and all affected services have been fully restored. The issue was traced to a component (Elasticsearch) that had not yet been migrated from Linode to our new provider, AWS. We are in the process of completing the migration of all services to AWS by the end of this week. Additionally, we have implemented measures to prevent similar issues in the future. We sincerely apologize for any inconvenience this outage may have caused and appreciate your patience and understanding.'
---
