---
layout: post
title: Temporary login issues
status: investigating
severity: degradation
date: 2022-10-05 05:45 GTM
resolvedDate: 2022-10-05 23:00 GTM
clusters: [ustx,usnj,uk,de,sg,wseu]
services: [admin]
incident_states:
- status: investigating
  content: "Some customers are experiencing trouble logging in. Our team is already applying a workaround and preparing a patch to resolve the issue entirely."
  date: 2022-10-05 06:30 GTM
- status: update
  content: "Issue rootcause identified and patch is being applied (as a minor mass update) to affected accounts."
  date: 2022-10-05 09:15 GTM
- status: resolved
  content: "Issue have have been resolved by a mass (minor) update to patched version 5.32.4.23"
---
