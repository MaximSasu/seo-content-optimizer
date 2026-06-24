# On-Page SEO

Goal: make a single page as easy as possible for search engines to understand and rank for its target keyword, without hurting the human reading experience. Deliver exact strings the user can paste, with character counts.

## The on-page checklist

Work through these for the page. For each, give the recommended value, not just a note that it needs work.

### Title tag

The single most important on-page element. It is the clickable headline in search results.

- Keep it roughly 50 to 60 characters (about 600 pixels) so it does not truncate.
- Put the primary keyword near the front, naturally.
- Make it compelling, not just keyword-stuffed. It competes for a click against nine other results.
- Add the brand at the end for non-home pages: `Primary Keyword Phrase | Brand`.

Example. Page about olive wood cutting boards:
Weak: `Cutting Boards - Home`
Strong: `Olive Wood Cutting Boards, Handmade in Crete | Olive Wood Work` (60 chars)

### Meta description

Does not directly affect rankings, but a good one lifts click-through, which does.

- Around 140 to 160 characters.
- Include the primary keyword (it gets bolded when it matches the query).
- Write it as ad copy: state the benefit and add a soft call to action.

Example: `Handmade olive wood cutting boards from Crete. Naturally antibacterial, built to last a lifetime. Free engraving and Canada-wide shipping.` (137 chars)

### URL slug

- Short, lowercase, words separated by hyphens.
- Include the primary keyword, drop filler words (a, the, and).
- Avoid dates, IDs, and parameters where possible.

Good: `/olive-wood-cutting-boards`
Bad: `/products/item?id=10482&cat=kitchen`

### Headings (H1 to H6)

- Exactly one H1 per page, containing the primary keyword. It is usually the visible page title.
- Use H2s for main sections and H3s for subsections, in a logical hierarchy (do not skip levels for styling).
- Work secondary keywords and the actual questions people ask into subheadings. Question-style H2s win featured snippets and AI Overview citations.

### Body content

- Place the primary keyword in the first 100 words, naturally.
- Cover the topic thoroughly. Use secondary keywords and synonyms (semantic SEO) rather than repeating the exact phrase. Modern search understands meaning, so write naturally and the related terms will appear on their own.
- No keyword stuffing. If a sentence reads awkwardly because of a keyword, rewrite it. There is no magic density number; relevance and completeness matter, repetition does not.
- Break text into short paragraphs, with lists and tables where they genuinely help. Scannable pages keep readers, and dwell time is a quality signal.

### Images

- Descriptive file names: `olive-wood-cutting-board-crete.jpg`, not `IMG_4821.jpg`.
- Alt text that describes the image for screen readers and crawlers, including the keyword only where it fits naturally.
- Compress for fast loading (see technical-audit.md). Large images are the most common page-speed killer.

### Internal links

- Link out to 2 to 5 relevant pages on the same site, using descriptive anchor text (the visible link words). Anchor text tells search engines what the target page is about, so "olive wood spoons" beats "click here".
- Link new posts to relevant cornerstone pages, and add links from existing high-authority pages back to the new one so it inherits authority.
- This is one of the highest-leverage and most-neglected tactics. A site with strong internal linking ranks pages it otherwise could not.

### Outbound links

- Link to credible external sources where it supports a claim. It signals trust and good neighborhood, and does not "leak" meaningful ranking power for normal use.

### Structured data (schema)

- Add the schema type that matches the page: Article or BlogPosting for posts, Product plus Review/AggregateRating for products, FAQPage for Q&A sections, LocalBusiness for a location, BreadcrumbList for navigation, HowTo for step guides.
- Schema powers rich results (stars, FAQs, prices in the SERP) and helps AI engines parse the page. See technical-audit.md for snippets.

## Output format

Return a compact optimization block the user can act on:

```
Title tag (58):  <exact string>
Meta desc (152): <exact string>
URL slug:        <exact string>
H1:              <exact string>
Suggested H2s:   - <heading>  - <heading>  ...
Primary keyword: <term>  | placed in: title, H1, first paragraph, one H2
Secondary terms to weave in: <list>
Internal links to add: <page> (anchor: "<text>"), ...
Schema to add: <type>
Image alt text: <per image>
```

Then list any content gaps versus the pages currently ranking, so the user knows what to add to compete.
