---
_build:
  publishResources: false
  render: never
  list: never
---

If you have another *A* or *AAAA* record in your Cloudflare **DNS** or your Cloudflare **Load Balancer** provides another origin in the same pool, **Zero-Downtime Failover** automatically retries requests to your origin even before a Load Balancing decision is made.

{{<render file="_zero-downtime-failover-retry-on-error.md" productFolder="fundamentals">}}