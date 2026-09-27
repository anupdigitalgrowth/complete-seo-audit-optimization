# Canonicalization Audit

## Purpose

This audit inspects canonical tag (`<link rel="canonical" href="..." />`) implementation to ensure search engines recognize the master version of each page, preventing duplicate content issues caused by parameters, trailing slashes, or HTTP/HTTPS variants.

## Scope

[ADD PAGES / URLS CHECKED: e.g., All indexed URLs, parameterized URLs, pagination, and trailing slash variants]

## Audit Method

[ADD ACTUAL METHOD / TOOLS: e.g., Screaming Frog Canonical Tag Extraction, Chrome DevTools DOM inspection, Google Search Console URL Inspection]

## Checklist

- [ ] Verify every indexable page has a valid, self-referential canonical tag
- [ ] Ensure canonical URLs are absolute (e.g., `https://domain.com/page/`) not relative (`/page/`)
- [ ] Confirm canonical tags match domain protocol (HTTPS) and preferred domain format (WWW vs Non-WWW)
- [ ] Check parameterized/session URLs canonicalize back to clean primary master URLs
- [ ] Verify paginated series canonicalize properly (Self-referential canonicals on page 2, 3, etc.)
- [ ] Ensure canonicalized pages are NOT blocked in `robots.txt` or marked `noindex`
- [ ] Check for conflicting canonical tags in HTML `<head>` vs. HTTP headers

## Findings

[ADD ACTUAL FINDINGS: Detail missing canonical tags, relative canonicals, or self-canonicalization mismatches.]

## Evidence

[ADD SCREENSHOT / DATA / REFERENCE: Provide code snippets of `<head>` canonical tags or Screaming Frog canonical export data.]

## Priority

[High / Medium / Low / Informational]

## Recommendation

[ADD ACTUAL RECOMMENDATION: Detail how to configure dynamic canonical tags in CMS or head templates.]

## Implementation Status

[Not Started / In Progress / Completed / Not Applicable]

## Notes

[ADD ADDITIONAL NOTES: Note any cross-domain canonical implementations if applicable.]
