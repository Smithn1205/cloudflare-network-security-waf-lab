# Security Rules

## Custom Rules
Cloudflare showed **5/5 custom rules**, with **4 active**.

### 1. Malicious/suspicious request blocking
**Action:** Block

Targets include SQL-injection patterns, directory traversal, sensitive files such as `/.env` and `/.git/config`, backup files, executable files, XML-RPC, sensitive filesystem paths, command-injection-style parameters, and empty User-Agent values.

### 2. Old browser challenge
**Condition:** HTTP Version equals HTTP/1.0  
**Action:** Managed Challenge

### 3. Verified/good bot handling
Matches verified bots and selected verified categories.  
**Action:** Skip

### 4. Development phase
**Condition:** `http.request.uri.path contains "/about.html" and not ip.src in $homeip`  
**Action:** Block

### 5. IP-based test rule
**Condition:** `ip.src in $homeip`  
**Action:** Skip  
**Status:** Disabled

## Rate Limiting
**Login protection**
- Path: `/login.html`
- Action: **Block**
- Status: Active

## Managed Protection
The captured Security Overview showed running detection categories for:
- Web application exploits
- DDoS attacks
- API abuse
- Fraud protection

These managed protections are documented separately from the custom rules.

## Evidence
- `screenshots/04-security-rules.png`
- `screenshots/05-rate-limiting.png`
- `screenshots/05-rate-limit-test-error-1015.png`
- `screenshots/06-security-overview.png`
- `screenshots/07-turnstile-analytics.png`
