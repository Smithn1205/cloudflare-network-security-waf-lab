# Screenshot Evidence Guide

Upload these files here using the exact names.

| File | Capture |
|---|---|
| `01-dns-records.png` | DNS records + proxy status |
| `02-ssl-tls-overview.png` | Flexible mode + TLS traffic |
| `03-edge-certificates.png` | Universal SSL + certificate coverage/expiry |
| `04-security-rules.png` | 5/5 custom rules + actions/status |
| `05-rate-limiting.png` | Login protection + /login.html + Block |
| `05-rate-limit-test-error-1015.png` | Live rate-limit test showing Cloudflare Error 1015 |
| `06-security-overview.png` | 39.76k requests + 19.14% mitigated + detection tools |
| `07-turnstile-analytics.png` | Live Turnstile analytics: 26 challenges, 4 solved, 84.62% likely bot, and Siteverify status |
| `08-turnstile-solve-rates.png` | Turnstile solve rates: 13 solved, 4 interactive, 9 non-interactive, 0 pre-clearance |
| `09-turnstile-challenge-outcomes.png` | Turnstile challenge outcomes: 38 issued, 13 solved, 25 unsolved, 34.21% likely human, 65.79% likely bot |
| `10-cache-rule-domain.png` | Domain cache rule + 1-day Edge TTL + 4-hour Browser TTL |
| `11-cache-rule-login-bypass.png` | /login.html + Bypass cache |
| `12-cache-overview.png` | Cache Overview / missed-cache data |
| `13-observatory-before-smart-shield.png` | 40.18% cache hit ratio + performance |
| `14-security-analytics-30d.png` | 30-day security metrics |
| `15-security-analytics-24h.png` | 2.6k requests + 706 mitigated |
| `16-origin-analytics.png` | Origin response/connection metrics |
| `17-http-traffic-overview.png` | HTTP Traffic overview: cache hit ratio, 4xx/5xx errors, and synthetic monitoring |
| `18-observatory-current.png` | Current Observatory snapshot: Core Web Vitals, TTFF, and TTLB performance | 24h HTTP Traffic + 8.58 MB bandwidth + cached/uncached bandwidth |
| `18-security-settings.png` | Optional security settings |
| `19-smart-shield-enabled.png` | Optional Smart Shield status |
| `20-cloudflare-trace.png` | Only if you later obtain a real Cloudflare Trace result |

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
