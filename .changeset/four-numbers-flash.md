---
'@astrojs/telemetry': patch
'@astrojs/webapi': patch
---

Fix telemetry crashing astro build/dev when using optional integrations

Telemetry will now ignore falsy integration values