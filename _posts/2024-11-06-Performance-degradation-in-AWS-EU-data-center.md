---
layout: post
title: Performance degradation in AWS EU data center
status: resolved
severity: degradation
date: 2024-11-06 13:25 UTC
resolvedDate: 2024-11-06 13:46 UTC
clusters: [ec1]
services: [admin,calls,tickets,emails]
incident_states: 
- status: investigating
  content: 'Few customers on our AWS EU - Frankfurt data center are currently experiencing an unexpected performance degradation. Our infrastructure team have identified the cause of the issue and already works on restoring full functionality as soon as possible. We understand the inconvenience this may cause and assure you that we are taking all necessary steps to resolve this incident promptly. We will continue to provide updates on our status page and will notify you once the services are fully restored. We appreciate your patience and understanding during this time.'
- status: resolved
  content: 'We are pleased to inform you that the recent performance degradation has been successfully resolved and affected only small number of customers. Only accounts which reside on one specific pushstream were affected. We will implemented push stream events count monitoring to avoid similar cases in the future. We sincerely apologize for any inconvenience this degradation may have caused and appreciate your patience and understanding. Our team will keep monitoring the status of our servers.'
---
