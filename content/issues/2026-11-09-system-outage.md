---
title: System unavailable (Jetstream2 storage failures)
date: 2026-11-09 09:49:00
resolved: true
resolvedWhen: 2026-11-09 13:57:00
severity: disrupted
affected:
  - API
  - Website
  - Station Widget
  - Kubernetes
  - Jetstream2
section: issue
---

*Investigating* - System monitoring reported API is offline. {{< track "2026-11-09 09:49:00" >}}

*Identified* - Jetstream2 is offline due to storage failures. "Jetstream2 is experiencing storage failures and is currently unavailable. System administrators are currently investigating and are working on recovering the system." https://jetstream.status.io/pages/incident/61dc808a7e9a82053ce739d2/6af207c0f7988a0425ce6537 {{< track "2026-11-09 11:33:00" >}}

*Resolved* - Jetstream2 back online after storage failures. API and all services are back up. {{< track "2026-11-09 13:57:00" >}}
