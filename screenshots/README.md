# Screenshot Evidence Guide

These are the **12 screenshots currently uploaded** to the project. The list is intentionally limited to the core evidence.

| File | Capture |
|---|---|
| `01-dns-records.png` | DNS records + proxy status |
| `02-ssl-tls-overview.png` | Flexible mode + TLS traffic |
| `03-security-rules.png` | 5/5 custom rules + actions/status |
| `04-rate-limiting.png` | Live rate-limit test showing Cloudflare Error 1015 |
| `05-turnstile-analytics-overview.png` | Turnstile analytics: 38 challenges issued, 13 solved, 34.21% likely human |
| `06-turnstile-challenge-outcomes.png` | Turnstile outcomes: 38 issued, 13 solved, 25 unsolved, 65.79% likely bot |
| `07-cache-rule-domain.png` | Domain cache rule + 1-day Edge TTL + 4-hour Browser TTL |
| `08-cache-rule-login-bypass.png` | /login.html + Bypass cache |
| `09-observatory-before-smart-shield.png` | Pre-Smart-Shield Observatory baseline: 40.18% cache hit ratio + performance |
| `10-security-analytics-30d.png` | 30-day security metrics |
| `11-origin-analytics-overview.png` | Origin Analytics overview: response time, errors, connection/TCP/TLS metrics |
| `12-origin-analytics-endpoints.png` | Origin Analytics Top Endpoints: endpoint-level response and error metrics |

## Future evidence

If useful later, additional screenshots can be added for:
- current Observatory after Smart Shield has been active for a meaningful period
- Smart Shield enabled/status
- a real Cloudflare Trace result

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
