---
title: System unavailable (Jetstream2 storage failures)
date: 2026-11-18 04:15:00
resolved: true
resolvedWhen: 2026-11-18 06:00:00
severity: disrupted
affected:
  - API
  - Website
  - Station Widget
  - Kubernetes
  - Jetstream2
section: issue
---

*Investigating* - System monitoring reported API is offline. {{< track "2026-11-18 04:15:00" >}}

*Identified* - Jetstream2 is offline due to storage failures. Confirmed via Jetstream2 Slack; their status page has not been fully updated yet. Waiting for Indiana University Jetstream2 to restore storage and bring systems back online. https://jetstream.status.io/ {{< track "2026-11-18 05:15:00" >}}

*Resolved* - Jetstream2 storage appears restored as of approximately 10 PM Pacific. No confirmation or update was posted on the Jetstream2 status page. Dendra system services are back up. {{< track "2026-11-18 06:00:00" >}}

*Update* - Cleared several stuck backup pods. Continuing to monitor. {{< track "2026-11-18 17:18:00" >}}
