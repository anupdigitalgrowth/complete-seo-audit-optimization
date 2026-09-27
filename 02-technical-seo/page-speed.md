# Page Speed & Core Web Vitals Audit

## Purpose

This audit measures page load performance, rendering speed, and Core Web Vitals metrics (LCP, INP, CLS) on desktop and mobile devices to improve user experience and satisfy search ranking criteria.

## Scope

[ADD PAGES / URLS CHECKED: e.g., Homepage, high-traffic landing pages, service pages, media-rich blog posts]

## Audit Method

[ADD ACTUAL METHOD / TOOLS: e.g., Google PageSpeed Insights (PSI API), Chrome DevTools Lighthouse, WebPageTest, GSC Core Web Vitals Report]

## Checklist

- [ ] Measure Largest Contentful Paint (LCP) (Target: ≤ 2.5 seconds)
- [ ] Measure Interaction to Next Paint (INP) / First Input Delay (FID) (Target: INP ≤ 200 ms)
- [ ] Measure Cumulative Layout Shift (CLS) (Target: ≤ 0.1)
- [ ] Audit First Contentful Paint (FCP) and Time to First Byte (TTFB) (Target: TTFB ≤ 0.8s)
- [ ] Check render-blocking JavaScript and CSS resources
- [ ] Audit image compression, responsive sizing, and next-gen format usage (WebP/AVIF)
- [ ] Verify browser caching headers and server-level compression (Gzip/Brotli)
- [ ] Inspect third-party scripts (Analytics, chat widgets, ads) impacting execution time

## Findings

[ADD ACTUAL FINDINGS: Detail failing Core Web Vitals scores, slow TTFB, uncompressed images, or heavy JS execution.]

## Evidence

[ADD SCREENSHOT / DATA / REFERENCE: Attach PageSpeed Insights scorecards, Lighthouse performance trace diagrams, or GSC Core Web Vitals charts.]

## Priority

[High / Medium / Low / Informational]

## Recommendation

[ADD ACTUAL RECOMMENDATION: Specify image compression steps, lazy-loading attributes, code minification, or CDN integration.]

## Implementation Status

[Not Started / In Progress / Completed / Not Applicable]

## Notes

[ADD ADDITIONAL NOTES: Note server hosting infrastructure details or caching plugin configurations.]
