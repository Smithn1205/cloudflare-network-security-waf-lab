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

## 24-Hour Web Traffic & Bandwidth Snapshot
Cloudflare Web Traffic showed:
- Total requests: **2.6k**
- Cached requests: **144**
- Uncached requests: **2.46k**
- Total bandwidth: **8.58 MB**
- Cached bandwidth: **169.41 kB**
- Uncached bandwidth: **8.41 MB**
- Total unique visitors: **76**
- Maximum unique visitors per hour: **20**
- Minimum unique visitors per hour: **8**

The cached bandwidth represented approximately **1.97%** of total bandwidth for this snapshot. This is a traffic snapshot and should not be interpreted as a long-term cache-performance measurement.

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
- `screenshots/14-security-analytics-30d.png`
- `screenshots/15-security-analytics-24h.png`
- `screenshots/16-origin-analytics.png`
- `screenshots/18-http-traffic-bandwidth.png`
