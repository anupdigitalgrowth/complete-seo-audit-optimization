# HTTPS & Security Audit

## Purpose

This audit checks site security, SSL/TLS certificate configuration, HTTP-to-HTTPS redirect enforcement, and mixed content issues to guarantee secure user connections and maintain search engine trust signals.

## Scope

[ADD PAGES / URLS CHECKED: e.g., Domain root, subdomains, internal assets (images, CSS, JS), third-party scripts]

## Audit Method

[ADD ACTUAL METHOD / TOOLS: e.g., SSL Labs Server Test, Screaming Frog Security Crawl, Chrome DevTools Security Tab, WhyNoPadlock.com]

## Checklist

- [ ] Confirm valid SSL/TLS certificate is installed and active
- [ ] Verify HTTP automatically redirects to HTTPS via 301 Permanent Redirect
- [ ] Check Non-WWW vs. WWW domain variants redirect to single secure HTTPS destination
- [ ] Audit for mixed content warnings (HTTP assets loaded on HTTPS pages)
- [ ] Validate HTTP Strict Transport Security (HSTS) header implementation
- [ ] Ensure canonical tags and sitemap entries specify `https://` protocol
- [ ] Check security header flags (X-Content-Type-Options, X-Frame-Options, Content-Security-Policy)

## Findings

[ADD ACTUAL FINDINGS: Detail insecure HTTP links, mixed content warnings, or missing 301 redirects.]

## Evidence

[ADD SCREENSHOT / DATA / REFERENCE: Attach SSL Labs score certificate screenshot or DevTools Security log output.]

## Priority

[High / Medium / Low / Informational]

## Recommendation

[ADD ACTUAL RECOMMENDATION: Specify server-level redirect rules (.htaccess, NGINX, Cloudflare) and mixed content fixes.]

## Implementation Status

[Not Started / In Progress / Completed / Not Applicable]

## Notes

[ADD ADDITIONAL NOTES: Note SSL certificate renewal schedule or CDN SSL configuration.]
