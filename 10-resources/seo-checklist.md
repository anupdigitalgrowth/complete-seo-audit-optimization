# Master SEO Audit & Optimization Checklist

This comprehensive reference checklist serves as a reusable operational framework covering Technical SEO, On-Page SEO, Local SEO, Content SEO, and Web Analytics.

---

## Technical SEO Checklist

- [ ] **Crawlability:** Verify crawler access in Googlebot simulator; test crawl depth (< 3 clicks).
- [ ] **Indexability:** Audit Meta Robots tags (`index, follow`) and X-Robots-Tag headers across all URLs.
- [ ] **XML Sitemap:** Ensure XML sitemap exists, contains only 200 OK canonical URLs, and is submitted in GSC.
- [ ] **Robots.txt:** Validate syntax, ensure CSS/JS files are accessible, and include sitemap directive.
- [ ] **Canonicalization:** Confirm self-referential absolute canonical tags on all indexable pages.
- [ ] **HTTPS & Security:** Verify SSL/TLS certificate, 301 HTTPS redirects, HSTS headers, and zero mixed content.
- [ ] **Redirects:** Eliminate 302 temporary redirects on permanent moves; resolve 301 redirect chains.
- [ ] **Broken Links:** Scan site for internal and external 404 dead links; implement 301 redirects or update links.
- [ ] **Mobile Usability:** Verify viewport settings, responsive breakpoint layouts, and touch element padding.
- [ ] **Page Speed:** Audit TTFB (< 0.8s), render-blocking resources, asset minification, and browser caching.
- [ ] **Core Web Vitals:** Pass LCP (≤ 2.5s), INP (≤ 200ms), and CLS (≤ 0.1) thresholds on mobile and desktop.
- [ ] **Structured Data:** Implement valid Schema.org JSON-LD markup (Organization, Article, Product, FAQ).

---

## On-Page SEO Checklist

- [ ] **Title Tags:** Write unique title tags (50-60 chars) with primary keyword placed front-loaded.
- [ ] **Meta Descriptions:** Write compelling meta descriptions (140-155 chars) with clear call-to-action.
- [ ] **H1 Heading:** Ensure exactly one unique H1 tag containing the primary keyword per page.
- [ ] **H2/H3 Hierarchy:** Organize content using logical subheadings containing secondary/LSI keywords.
- [ ] **URL Structure:** Create short, lowercase, hyphenated URLs incorporating target keywords.
- [ ] **Keyword Density & Focus:** Natural keyword integration without keyword stuffing (< 2.5% density).
- [ ] **Search Intent Matching:** Ensure content format aligns with user search intent (Informational, Transactional, etc.).
- [ ] **Internal Links:** Contextually link out to target landing pages using descriptive anchor text.
- [ ] **Image Compression:** Compress image files (< 100KB) and convert to next-gen formats (WebP/AVIF).
- [ ] **Image ALT Text:** Add descriptive, accessible ALT text containing relevant keywords to all images.
- [ ] **Content Depth:** Ensure thorough topic coverage matching top-ranking competitor benchmarks.

---

## Local SEO Checklist

- [ ] **Google Business Profile (GBP):** Claim, verify, and complete 100% of GBP profile information.
- [ ] **NAP Consistency:** Ensure Name, Address, and Phone Number match across website, GBP, and web directories.
- [ ] **Local Landing Pages:** Build location-specific landing pages optimized for geo-targeted keywords.
- [ ] **Review Strategy:** Implement automated customer review acquisition and respond to customer feedback.
- [ ] **Local Citations:** Submit business details to top local & industry directory databases (Yelp, YellowPages, Bing Places).
- [ ] **Local Keywords:** Integrate local geo-modifiers (e.g., "SEO agency in City", "near me") into content & metadata.

---

## Content SEO Checklist

- [ ] **Search Intent Validation:** Verify whether target keywords demand blog guides, product pages, or comparison lists.
- [ ] **Content Depth & E-E-A-T:** Showcase original research, expert quotes, author bios, and trustworthy references.
- [ ] **Content Gap Analysis:** Identify missing subtopics and questions answered by top 3 SERP competitors.
- [ ] **Topic Clusters & Silos:** Group related articles around pillar pages with bidirectional internal linking.
- [ ] **Internal Linking Architecture:** Link high-authority pillar content down to sub-topic supporting articles.
- [ ] **Content Freshness:** Establish periodic content audit schedules to update outdated statistics, links, and dates.

---

## Analytics & Tracking Checklist

- [ ] **Google Search Console (GSC):** Verify Domain/URL Prefix properties, inspect index coverage, and track queries.
- [ ] **Google Analytics 4 (GA4):** Configure GA4 measurement ID, custom dimensions, and cross-domain tracking.
- [ ] **Goal & Event Tracking:** Set up conversion events for form submissions, phone clicks, and purchases.
- [ ] **Conversion Attribution:** Test GA4 conversion paths, referral exclusions, and UTM campaign parameters.
- [ ] **Performance Reporting:** Build monthly reporting dashboards tracking organic traffic, CTR, rankings, and conversions.
