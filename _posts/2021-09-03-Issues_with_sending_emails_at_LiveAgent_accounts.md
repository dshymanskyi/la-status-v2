---
layout: post
title: Issues with sending emails at LiveAgent accounts
status: Resolved
severity: degradation
date: 2021-09-03 18:15
resolvedDate: 2021-09-03 20:15 GTM+2
clusters: [ustx,usnj,sg,de,uk,wseu] 
services: [emails]
incident_states:
- status: investigating
  content: "Some of our customers (early adopters using already version 5.25) may experience issues with sending emails at their accounts"
- status: update
  content: "Emails are being being queued, there appears to be a lot of emails scheduled to be sent"
- status: resolved
  content: "Issue was affecting very small number of customers running already on newest 5.25 version (version 5.25 is not yet officially released and so far used only by very few customers). In case of bigger attachment (20+ MB) added to an email, email queue get stuck in the outbox and new emails from the affected email address were not being send until the stucked outbox was manually resolved by a hoftix. there will be an urgent bugfix released for 5.25 within the next days, before we would update any additional customers to this version."
  date: 2021-09-03 20:15 GTM+2
---
