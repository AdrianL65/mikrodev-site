# mikrodev-site

Studio root for **https://mikrodev.net**, served by GitHub Pages.

- `index.html`: one-screen studio page that links to each app's own sites (`<app>-support.mikrodev.net`, `<app>-legal.mikrodev.net`).
- `app-ads.txt`: **add once the AdMob publisher ID is confirmed.** AdMob looks for it at the root of the developer domain.
  Format: `google.com, pub-XXXXXXXXXXXXXXXX, DIRECT, f08c47fec0942fa0`
- Naming rule for new apps: `<app>-support` (home + help) and `<app>-legal` (privacy, terms, deletion), one repo each.

Do not remove the DNS records for `send.mikrodev.net` / `resend._domainkey` (Resend email) or the DMARC record.
The Turnstile CAPTCHA widget uses the hostname `mikrodev.net`; it does not load anything from this site.
