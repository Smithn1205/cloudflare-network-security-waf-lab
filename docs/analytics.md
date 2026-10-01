# Security & Origin Analytics

## 30-Day Security Snapshot
- Total requests: **39.76k**
- Mitigated: **19.14%**
- Served by Cloudflare: **19.97%**
- Served by origin: **60.89%**

## 24-Hour Security Snapshot
- **2.6k** requests
- **706** mitigated
- **186** served by Cloudflare
- **1.7k** served by origin

These are dashboard snapshots and are not presented as confirmed successful attacks.

## Origin Analytics
- Connection success rate: **68%**
- P95 response-time headline: **383 ms**
- Error rate: **0%**
- P50/P75: **201 ms**
- P95/P99: **229 ms**
- TCP handshake: **102 ms**
- TLS handshake: **1.4 ms**
- Response wait: **104 ms**

Observed paths included `/.s3cfg`, `/shop/.env`, `/dashboard/.env`, and `/gcp-key.json`. These are observed request paths only; successful compromise is not claimed.

## Evidence
- `screenshots/12-security-analytics-30d.png`
- `screenshots/13-security-analytics-24h.png`
- `screenshots/14-origin-analytics.png`
