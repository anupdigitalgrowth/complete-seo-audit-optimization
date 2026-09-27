# Crawlability Audit

## Purpose

This audit evaluates how effectively search engine bots (Googlebot, Bingbot) can access, navigate, and crawl the website's URLs without hitting crawl blocks, redirect loops, infinite loops, or excessive crawl budget waste.

## Scope

[ADD PAGES / URLS CHECKED: e.g., All site URLs, navigation menus, subdirectories, pagination URLs, and parameter URLs]

## Audit Method

[ADD ACTUAL METHOD / TOOLS: e.g., Screaming Frog SEO Spider (Googlebot User-Agent simulation), Google Search Console Crawl Stats report, Server Log File Analysis]

## Checklist

- [ ] Check HTTP status codes (Ensure primary URLs return 200 OK)
- [ ] Identify 404 Page Not Found errors and broken internal links
- [ ] Inspect 301 and 302 redirect chains and redirect loops
- [ ] Audit site crawl depth (Ensure key pages are reachable within 3 clicks from homepage)
- [ ] Check for crawl budget waste (Faceted navigation, URL parameters, duplicate content URLs)
- [ ] Verify JavaScript rendering accessibility for crawler bots
- [ ] Test orphan page presence (Pages with zero internal incoming links)

## Findings

[ADD ACTUAL FINDINGS: Detail crawl blocks, redirect chains, 404 errors, or high crawl depth pages found.]

## Evidence

[ADD SCREENSHOT / DATA / REFERENCE: Attach crawl visualization graphs, Screaming Frog export references, or GSC crawl stats screenshots.]

## Priority

[High / Medium / Low / Informational]

## Recommendation

[ADD ACTUAL RECOMMENDATION: Detail how to fix broken links, trim redirect chains, or update navigation structures.]

## Implementation Status

[Not Started / In Progress / Completed / Not Applicable]

## Notes

[ADD ADDITIONAL NOTES: Include any notes on staging vs. production crawling behaviors or server response times.]
