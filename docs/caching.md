# Caching & Performance

## Domain Cache Rule
Expression: `(http.host eq "practicecf.cfd")`

- Cache eligibility: **Eligible for cache**
- Edge TTL: **1 day**
- Browser TTL: **4 hours**
- Edge TTL ignores the origin Cache-Control header.
- Browser TTL overrides the origin TTL.
- Rule order: first.

## Login Cache Bypass
Expression: `(http.request.uri.path eq "/login.html")`

**Action:** Bypass cache

This rule runs after the domain-level cache rule.

## Observatory Snapshot
Captured before Smart Shield activation:
- Cache hit ratio: **40.18%**
- Origin: **59.82%**
- P75 request time: **226 ms**
- P75 response time: **3 ms**
- Core Web Vitals: no data available

## Smart Shield
Smart Shield was activated on **1 October 2026**. No performance improvement is claimed yet.

## Evidence
- `screenshots/08-cache-rule-domain.png`
- `screenshots/09-cache-rule-login-bypass.png`
- `screenshots/10-cache-overview.png`
- `screenshots/11-observatory-before-smart-shield.png`
