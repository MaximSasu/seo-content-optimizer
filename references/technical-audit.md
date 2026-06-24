# Technical and Content Audit

Goal: find what is holding a site or page back and return a prioritized fix list, highest impact and lowest effort first. Cover technical health, on-page quality, content gaps, and AEO readiness.

When you have web access, inspect the live pages. When a connector (Ahrefs, Search Console, Semrush, PageSpeed) is available, pull real data and say so. Otherwise audit what you can observe and reason transparently about the rest.

## Audit areas

### 1. Indexing and crawlability

If a page is not indexed, nothing else matters.

- Is the page indexable (not blocked by robots.txt, not `noindex`)?
- Does the site have an XML sitemap, submitted to Google Search Console?
- Is `robots.txt` sane (not accidentally blocking important sections)?
- Are there crawl traps, infinite parameters, or orphan pages (no internal links pointing to them)?
- Canonical tags: does each page declare a canonical URL to avoid duplicate-content splits?

### 2. Site architecture and internal linking

- Is the structure shallow (important pages within 3 clicks of home)?
- Do related pages link to each other? Are there cornerstone pages that everything supports?
- Any orphan pages or broken internal links (404s)?
- Is anchor text descriptive rather than "click here"?

### 3. Page speed and Core Web Vitals

Speed is a ranking factor and a conversion factor. Check (PageSpeed Insights if available):

- **LCP** (Largest Contentful Paint): under 2.5s. Usually hurt by large unoptimized images and slow servers.
- **INP** (Interaction to Next Paint): under 200ms. Hurt by heavy JavaScript.
- **CLS** (Cumulative Layout Shift): under 0.1. Hurt by images/ads without reserved space.
- Common fixes: compress and lazy-load images, serve next-gen formats (WebP/AVIF), minify CSS/JS, use a CDN, reduce third-party scripts.

### 4. Mobile and rendering

- Mobile-friendly and responsive? Google indexes mobile-first, so the mobile version is the version that ranks.
- Tap targets, font sizes, no horizontal scroll.
- Content parity: the mobile page must contain the same content as desktop, not a stripped-down version.

### 5. HTTPS and security

- Site served over HTTPS with a valid certificate. Mixed content (http assets on an https page) should be fixed.

### 6. On-page quality (per key page)

Run the on-page checklist from `on-page-seo.md`: title, meta, headings, keyword placement, alt text, internal links, schema. Flag missing or weak elements.

### 7. Content quality and gaps

- Thin or duplicate pages that should be improved, merged, or removed.
- Keyword cannibalization: multiple pages targeting the same term, splitting their own rankings.
- Outdated content that needs refreshing (old stats, old years, dead links).
- Missing topics: clusters competitors cover that this site does not. Compare against the keyword map.
- Pages that rank on page two: often the fastest wins, since a modest improvement can push them onto page one.

### 8. Structured data and AEO readiness

- Is relevant schema present and valid (test with Google's Rich Results Test)?
- Do key pages have a crisp top-of-page answer block and question-style headings that AI engines can quote?
- Is authorship, business info, and contact detail clear (E-E-A-T signals)?

## Schema snippets

FAQ (great for AEO and rich results):

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "FAQPage",
  "mainEntity": [{
    "@type": "Question",
    "name": "How do I care for an olive wood board?",
    "acceptedAnswer": {"@type": "Answer", "text": "Hand wash, dry upright, and oil monthly with food-safe mineral oil."}
  }]
}
</script>
```

Article:

```html
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "BlogPosting",
  "headline": "...",
  "author": {"@type": "Person", "name": "..."},
  "datePublished": "2026-01-01",
  "image": "..."
}
</script>
```

Product, LocalBusiness, HowTo, and BreadcrumbList follow the same pattern; match the type to the page.

## Output: the prioritized action list

Do not dump a flat checklist. Score each issue by impact and effort and sort so the user knows what to do first:

| Priority | Issue | Why it matters | The fix | Effort |
|----------|-------|----------------|---------|--------|

Lead with quick wins (high impact, low effort: a missing title tag, an unindexed money page, an image that tanks LCP). Then strategic items (content gaps, architecture). Close with a short "do these three things this week" summary so the user is not paralyzed by the full list.
