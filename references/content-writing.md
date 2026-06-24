# SEO Content Writing

Goal: produce content that is the best available answer to the searcher's query, structured so search engines and AI answer engines rank and cite it. A draft that ranks but bores the reader fails; so does a beautiful draft no one can find.

## Before writing

1. **Confirm the primary keyword and intent.** If the user has not done keyword research, do it first (see keyword-research.md) or at least settle the one keyword and what the searcher wants.
2. **Read the top 3 to 5 ranking pages** for that keyword (use web access if available). Note their depth, structure, subtopics, and angle. Your job is to cover everything they cover and add what they miss: a fresher stat, a clearer explanation, first-hand experience, a better example, an original visual.
3. **Decide the content type** the intent calls for: how-to guide, listicle, comparison, definition/explainer, case study, product page. Match what already ranks.
4. **Settle the angle.** What makes this version worth reading over the ten that exist? Unique experience, a contrarian take, more current data, a simpler framework.

## Structure that ranks

### Title (H1)

Compelling and specific, primary keyword near the front. Numbers, the year, and a clear benefit raise click-through. "How to Season a Cutting Board (and Make It Last 20 Years)" beats "Cutting Board Care".

### Opening (the first 100 words)

- Answer or frame the query immediately. Do not bury the point under a personal saga.
- Include the primary keyword naturally in the first sentence or two.
- For informational queries, put a direct, self-contained answer of 40 to 60 words near the very top. This is what gets pulled into featured snippets and AI Overviews. State the answer plainly, then expand below.

### Body

- Logical H2/H3 sections, several of them phrased as the actual questions people ask (pull these from "People also ask" and keyword research). Question headings win snippet and AI citations.
- Short paragraphs (2 to 4 sentences). Use lists, tables, and bolded key terms where they aid scanning, not as decoration.
- Cover subtopics the ranking pages cover, plus the gaps. Depth signals expertise, but every sentence must earn its place; padding to hit a word count hurts more than it helps.
- Demonstrate experience and cite credible sources (E-E-A-T). First-hand detail and real data are what AI engines and discerning readers trust.
- Weave in secondary keywords and synonyms naturally. Write for a human and the semantic coverage takes care of itself.

### Internal links

- Link to 2 to 5 related pages with descriptive anchor text as you write, and note them inline so the user can wire them up. Always include a path toward a conversion or cornerstone page where it fits.

### Conclusion and CTA

- Summarize the key takeaway and give one clear next step (subscribe, shop, read the related guide). Every page should have a job beyond being read.

### Media

- Suggest images, diagrams, or a short table at the points where they help. Give descriptive alt text and file names for each (see on-page-seo.md).

## Writing quality

- Write naturally and specifically. Avoid filler ("In today's fast-paced world"), hollow transitions, and the same three-item list rhythm on every line. Vary sentence length.
- Be accurate. A single wrong fact damages trust with both readers and AI engines that weigh reliability.
- Match the site's brand voice. If you have samples of existing content, mirror their tone and reading level.
- Do not write like a robot trying to please a robot. Google's helpful-content systems and human readers both punish that.

## AEO: getting cited by AI answer engines

AI Overviews, ChatGPT, and Perplexity increasingly intercept clicks. To be the source they quote:

- Lead with a crisp, standalone answer (the 40 to 60 word block above).
- Use clear question-and-answer structure with descriptive headings.
- State facts plainly and attribute sources; AI engines favor content they can verify.
- Add FAQPage schema for question sections (see technical-audit.md).
- Keep information current; freshness helps for anything time-sensitive.

## Output

Deliver the complete, formatted draft (markdown by default). At the top or bottom, include a short SEO summary block:

```
Primary keyword: <term>   Intent: <type>
Suggested title tag: <string>
Suggested meta description: <string>
Suggested URL slug: <string>
Word count: <n>
Internal links suggested: <list>
Schema to add: <type>
```

Then save the draft as a file so the user can edit and publish it. A blog-post starter template is in `../assets/blog-post-template.md`.
