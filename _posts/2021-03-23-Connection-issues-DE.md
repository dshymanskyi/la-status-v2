---
layout: post
title: Connection issues affecting multiple DE accounts
status: investigating
severity: degradation
date: 2021-03-23 06:30
resolvedDate: 2021-03-29 12:00
clusters: [wseu,de]
services: [admin,calls,tickets,emails]
incident_states:
- status: investigating
  content: "We are investigating connection issues. Multiple DE accounts are affected. So far seems as an issue related to their ISP (Telekom). When connecting via different ISP, all works fine"
- status: update
  content: "Our network provider will reroute traffic from problematic provider. This change will be performed tonight. We expect that problems should not occur after. We will update this status once we have confirmation, that this change is completed."
  date: 2021-03-23 14:00
- status: update
  content: "Our network provider confirmed night change, but we still waiting for confirmation from ISP as issue unfortunately still persists. This really looks like a problem on the part of the ISP. We advice customers to possibly open a ticket with the ISP providing the MTR/tracert outputs: https://support.liveagent.com/795802-How-to-debug-networking-issues-when-LiveAgent-is-very-slow-or-not-loading-Cloud-accounts. 
Potential workaround: Use another ISP or if you can't use another uplink, tunnel the traffic through another ISP e.g. by Cloudflare WARP+ (not a plug) or other proxy/VPN services."
  date: 2021-03-24 08:00
- status: update
  content: "We have update in the ticket from our hosting provider, that they definetly see some problems and they are trying to resolve it with our network providers. We unfortunately do not know, when this will be resolved, so we still advise to temporarly use other ISP. "
  date: 2021-03-24 16:00
- status: resolved
  content: "Our hosting provider has just switched the traffic to another ISP. We have received confirmation from several affected customers that it fixed the issue."
  date: 2021-03-29 12:00
---
