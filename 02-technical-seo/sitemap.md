# XML Sitemap Audit

## Purpose

This audit evaluates the XML sitemap structure, formatting, freshness, and submission to ensure search engines have a clean, up-to-date roadmap of all primary canonical URLs.

## Scope

[ADD PAGES / URLS CHECKED: e.g., `/sitemap.xml`, `/sitemap_index.xml`, page sitemaps, post sitemaps, image sitemaps]

## Audit Method

[ADD ACTUAL METHOD / TOOLS: e.g., XML Sitemap Validator, Screaming Frog Sitemap Crawl mode, Google Search Console Sitemaps Report]

## Checklist

- [ ] Verify XML sitemap existence and location (e.g., `https://domain.com/sitemap.xml`)
- [ ] Ensure XML sitemap is referenced in `robots.txt`
- [ ] Verify XML sitemap format compliance with Sitemaps.org protocol standards
- [ ] Confirm XML sitemap contains ONLY 200 OK canonical URLs (No 301, 404, 5xx, or noindexed URLs)
- [ ] Check XML sitemap size limits (Max 50,000 URLs or 50MB per uncompressed sitemap file)
- [ ] Confirm submission and status in Google Search Console Sitemaps report
- [ ] Check last modification dates (`<lastmod>`) accuracy and dynamic updates

## Findings

[ADD ACTUAL FINDINGS: Detail sitemap validation errors, non-200 URLs found in sitemaps, or submission warnings.]

## Evidence

[ADD SCREENSHOT / DATA / REFERENCE: Attach GSC Sitemaps Report screenshot or sitemap XML snippet.]

## Priority

[High / Medium / Low / Informational]

## Recommendation

[ADD ACTUAL RECOMMENDATION: Specify sitemap regeneration rules, removal of non-canonical URLs, or GSC re-submission.]

## Implementation Status

[Not Started / In Progress / Completed / Not Applicable]

## Notes

[ADD ADDITIONAL NOTES: Note any CMS plugin settings (e.g., Yoast, Rank Math) controlling sitemap generation.]
