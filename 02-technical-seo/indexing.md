# Indexing Audit

## Purpose

This audit checks search engine indexation status to verify that indexable pages are properly indexed by Google, while non-indexable/utility pages (admin, login, staging, thank-you pages) are correctly excluded from the index.

## Scope

[ADD PAGES / URLS CHECKED: e.g., All published URLs, category pages, tags, thank-you pages, and GSC Page Indexing Report entries]

## Audit Method

[ADD ACTUAL METHOD / TOOLS: e.g., Google Search Console Page Indexing Report, Google `site:` search operator queries, Screaming Frog Meta Robots Extraction]

## Checklist

- [ ] Check Meta Robots tags (`<meta name="robots" content="index, follow">`) on primary pages
- [ ] Audit X-Robots-Tag HTTP headers for non-HTML files or specific directives
- [ ] Inspect Google Search Console "Discovered - currently not indexed" status
- [ ] Inspect Google Search Console "Crawled - currently not indexed" status
- [ ] Check for accidental `noindex` directives on important money pages
- [ ] Ensure utility, cart, search result, and admin pages have appropriate `noindex` rules
- [ ] Verify soft 404 errors reported in GSC Indexing Report

## Findings

[ADD ACTUAL FINDINGS: Detail indexation coverage issues, excluded pages, or accidental noindex flags.]

## Evidence

[ADD SCREENSHOT / DATA / REFERENCE: Insert GSC Indexing Coverage report screenshots or URL Inspection Tool outputs.]

## Priority

[High / Medium / Low / Informational]

## Recommendation

[ADD ACTUAL RECOMMENDATION: Specify meta tag adjustments, GSC URL re-indexing submission steps, or soft 404 remedies.]

## Implementation Status

[Not Started / In Progress / Completed / Not Applicable]

## Notes

[ADD ADDITIONAL NOTES: Note any canonical vs. indexing discrepancies or indexation lag observations.]
