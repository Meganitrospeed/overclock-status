---
section: issue
title: Gaming Panel unavailble
date: 2021-08-16T23:44:20.731Z
resolved: true
draft: false
informational: false
resolvedWhen: 2021-08-16T23:44:20.918Z
severity: disrupted
---
*Solution - We have disabled the re-enabled Argo tunnels, everything appears to be normalized, backend nodes might take a bit more to reconnect to the panel*

*Investigating* - We found that CF reenabled Argo tunnel on one of our servers, functionality we havent used in a long time, this made that all our traffic is getting redirected through Cloudflare something thats unplanned for