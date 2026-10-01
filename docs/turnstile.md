# Cloudflare Turnstile

## Configuration

A Cloudflare Turnstile widget is configured for `practicecf.cfd` and embedded in the static site's:
- `contact.html`
- `login.html`

Configuration observed in the Cloudflare dashboard:
- Mode: **Managed**
- Pre-clearance: **No pre-clearance**
- Hostname: `practicecf.cfd`

## Live Test / Analytics Snapshot

A live browser interaction generated Turnstile challenge activity visible in Cloudflare Analytics. The captured last-24-hour snapshot showed:

- **26 challenges issued**
- **4 challenges solved**
- **22 challenges unsolved**
- **15.38% likely human**
- **84.62% likely bot**
- 4 interactive solves
- 0 non-interactive solves
- 0 pre-clearance solves

This demonstrates that the widget is actively generating challenges and producing observable challenge analytics.

## Server-side Validation Status

Cloudflare currently reports:
- **Siteverify requests: 0**
- **Valid tokens: 0**
- **Invalid tokens: 0**

The static website currently does not perform a server-side Siteverify request. The frontend displays the Turnstile widget, but the application does not send the resulting token to Cloudflare's Siteverify endpoint for validation.

This is an intentional accuracy note: the project documents **widget deployment and challenge analytics**, not completed server-side token validation.

## Evidence

- `screenshots/07-turnstile-analytics.png`
- Source implementation: `contact.html` and `login.html`

## Security Note

Never place the Turnstile secret key in client-side HTML or commit it to GitHub. A future Siteverify implementation would require a server-side component or serverless function with the secret stored securely as an environment variable/secret.
