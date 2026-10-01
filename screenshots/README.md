# Screenshot Evidence Guide

Upload these files here using the exact names.

| File | Capture |
|---|---|
| `01-dns-records.png` | DNS records + proxy status |
| `02-ssl-tls-overview.png` | Flexible mode + TLS traffic |
| `03-edge-certificates.png` | Universal SSL + certificate coverage/expiry |
| `04-security-rules.png` | 5/5 custom rules + actions/status |
| `05-rate-limiting.png` | Login protection + /login.html + Block |
| `06-security-overview.png` | 39.76k requests + 19.14% mitigated + detection tools |
| `07-turnstile-analytics.png` | Turnstile analytics: challenges issued/solved, likely human/bot, and Siteverify status |
| `08-cache-rule-domain.png` | Domain cache rule + 1-day Edge TTL + 4-hour Browser TTL |
| `09-cache-rule-login-bypass.png` | /login.html + Bypass cache |
| `10-cache-overview.png` | Cache Overview / missed-cache data |
| `11-observatory-before-smart-shield.png` | 40.18% cache hit ratio + performance |
| `12-security-analytics-30d.png` | 30-day security metrics |
| `13-security-analytics-24h.png` | 2.6k requests + 706 mitigated |
| `14-origin-analytics.png` | Origin response/connection metrics |
| `15-http-traffic-bandwidth.png` | 24h HTTP Traffic + 8.58 MB bandwidth + cached/uncached bandwidth |
| `16-security-settings.png` | Optional security settings |
| `17-smart-shield-enabled.png` | Optional Smart Shield status |
| `18-cloudflare-trace.png` | Only if you later obtain a real Cloudflare Trace result |

## Redaction rules

Redact:
- origin/public IP addresses when unnecessary
- email addresses
- account IDs where unnecessary
- API tokens/keys
- passwords
- Turnstile secrets
- cookies/session values

Do not upload secrets just to make the screenshot look complete.
