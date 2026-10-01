# DNS & TLS

## DNS
Cloudflare is the DNS and reverse-proxy layer for `practicecf.cfd`.

Observed configuration:
- Apex A record configured and proxied.
- `www` CNAME points to the apex domain and is proxied.
- A separate CNAME is DNS-only.

Origin IP and verification values are intentionally omitted.

## SSL/TLS
- Current SSL/TLS mode: **Flexible**
- Universal SSL is active.
- Certificate covers `practicecf.cfd` and `*.practicecf.cfd`.
- Displayed certificate expiry: **10 December 2026**
- TLS 1.3 traffic was observed in Cloudflare analytics.
- Certificate Transparency Monitoring alerts were active.

## Evidence
- `screenshots/01-dns-records.png`
- `screenshots/02-ssl-tls-overview.png`
- `screenshots/03-edge-certificates.png`
