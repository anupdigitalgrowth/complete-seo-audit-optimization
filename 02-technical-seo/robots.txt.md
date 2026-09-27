# Robots.txt Audit

## Purpose

This audit analyzes the website's `robots.txt` file to ensure crawl directives correctly manage search engine bot traffic, allow access to critical asset files (CSS/JS), and prevent indexing of sensitive or redundant paths.

## Scope

[ADD PAGES / URLS CHECKED: e.g., `https://domain.com/robots.txt`, subdirectories, user agents, allow/disallow directives]

## Audit Method

[ADD ACTUAL METHOD / TOOLS: e.g., Google Search Console Robots.txt Tester, TechnicalSEO.com Robots.txt Fetcher, Direct browser inspection]

## Checklist

- [ ] Confirm `robots.txt` file is located in root directory (`https://domain.com/robots.txt`)
- [ ] Verify HTTP response status of `robots.txt` (Must be 200 OK)
- [ ] Ensure critical site sections (homepage, services, landing pages, blog) are NOT blocked
- [ ] Confirm CSS, JavaScript, and image files are NOT blocked from search bots
- [ ] Verify syntax correctness (`User-agent:`, `Disallow:`, `Allow:`, `Sitemap:`)
- [ ] Check for proper blocking of admin, login, staging, or internal search result URLs
- [ ] Confirm absolute URL link to primary XML sitemap is included

## Findings

[ADD ACTUAL FINDINGS: Detail syntax errors, unintended crawl blocks, or missing sitemap directives.]

## Evidence

[ADD SCREENSHOT / DATA / REFERENCE: Insert full raw text of existing robots.txt or GSC Robots Tester output screenshot.]

## Priority

[High / Medium / Low / Informational]

## Recommendation

[ADD ACTUAL RECOMMENDATION: Provide exact updated robots.txt directive blocks for deployment.]

## Implementation Status

[Not Started / In Progress / Completed / Not Applicable]

## Notes

[ADD ADDITIONAL NOTES: Note any bot-specific rules (e.g., Googlebot vs. Bingbot vs. AI crawlers).]
