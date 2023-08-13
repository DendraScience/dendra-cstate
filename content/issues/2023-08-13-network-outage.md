---
title: System unavailable (Jetstream2 upstream network outage)
date: 2023-08-08 13:04:07
resolved: true
resolvedWhen: 2023-08-13 17:30:00
severity: disrupted
affected:
  - API
  - Jetstream2
section: issue
---

*Investigating* - System monitoring reported API is offline. {{< track "2023-08-13 15:23:10" >}}

*Identified* - "There is a network outage upstream from Jetstream2 that is preventing access. Running VMs should be unaffected but they will likely not be accessible." https://status.io/pages/incident/61dc808a7e9a82053ce739d2/64d8fedaadb04b052efa19f8 {{< track "2023-08-13 16:03:00" >}}

*Update* - System monitoring reported API is online. {{< track "2023-08-13 16:48:13" >}}

*Resolved* - "Network engineers have resolved the upstream network issues..." {{< track "2023-08-13 17:30:00" >}}
