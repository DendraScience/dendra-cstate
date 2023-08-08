---
title: System unavailable (Jetstream2 power outage)
date: 2023-08-08 13:04:07
resolved: true
resolvedWhen: 2023-08-08 17:22:00
severity: disrupted
affected:
  - API
  - Kubernetes
  - Jetstream2
section: issue
---

*Investigating* - System monitoring reported API is offiline. {{< track "2023-08-08 13:04:07" >}}

*Identified* - Jetstream2 is offline due to a power outage "related to power maintenance in the IU Bloomington data center." https://jetstream.status.io/pages/incident/61dc808a7e9a82053ce739d2/64d2431d9fabff05350acbe0 {{< track "2023-08-08 13:29:00" >}}

*Resolved* - Jetstream2 back online after power outage. API and all services are back up. {{< track "2023-08-08 17:22:00" >}}
