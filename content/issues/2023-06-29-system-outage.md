---
title: System unavailable (Jetstream2 power outage)
date: 2023-06-29 19:59:10
resolved: true
resolvedWhen: 2023-06-30 03:30:00
severity: disrupted
affected:
  - API
  - Kubernetes
  - Jetstream2
section: issue
---

*Investigating* - System monitoring reported API is offline. {{< track "2023-06-29 19:59:10" >}}

*Identified* - Jetstream2 is offline due to a power outage caused by a "severe weather event." https://jetstream.status.io/pages/incident/61dc808a7e9a82053ce739d2/649de482843954053d13e4e0 {{< track "2023-06-29 20:07:00" >}}

*Resolved* - Jetstream2 back online after power outage. LoggerNet and station status pods found in error state due to distributed MinIO bug. Patched MinIO to restore service. API and all services are back up. {{< track "2023-06-30 03:30:00" >}}
