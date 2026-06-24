# SEO Content Optimizer (Claude Skill)

A reusable, platform-agnostic SEO and content skill for [Claude](https://claude.ai). It turns Claude into an SEO partner that can do keyword research, optimize pages on-page, write genuinely useful blog posts, and audit a site for technical and content issues. It works for any website: WordPress, Wix, Shopify, Webflow, custom sites, or plain HTML.

## What it does

The skill covers the four jobs that actually move search rankings:

1. **Keyword research** seed to cluster to page map, with search-intent tagging and difficulty signals (works with or without a paid keyword tool).
2. **On-page optimization** exact title tags, meta descriptions, URLs, headings, alt text, internal links, and schema, with character counts you can paste straight in.
3. **Content writing** SEO blog posts and articles structured to rank and to get cited by AI answer engines (Google AI Overviews, ChatGPT, Perplexity).
4. **Technical and content audit** a prioritized fix list (highest impact, lowest effort first) covering indexing, speed, internal linking, content gaps, and structured data.

It is built around one principle: help a real reader first, then make that help easy for search engines to find and trust. No keyword stuffing, no thin content, no manipulative tactics.

## What is inside

```
seo-content-optimizer/
  SKILL.md                      # the skill: routing + operating principles
  references/
    keyword-research.md         # find and map keywords
    on-page-seo.md              # optimize a single page
    content-writing.md          # write content that ranks
    technical-audit.md          # audit a site, prioritized fixes
  assets/
    blog-post-template.md       # ready-to-fill SEO blog post template
```

## How to install

This is a Claude skill (a folder with a `SKILL.md`).

- **Claude desktop (Cowork):** download or clone this repo, then in Claude go to **Settings > Capabilities** and add the `seo-content-optimizer` folder.
- **Claude Code / Agent SDK:** place the `seo-content-optimizer` folder in your skills directory.

## How to use it

Once installed, just ask Claude in plain language. The skill triggers on its own and asks a couple of quick questions first (your site, target keyword, audience). Examples:

- "Write an SEO blog post about how to season a cutting board."
- "Do keyword research for handmade leather wallets."
- "Optimize this page for SEO: [paste URL or draft]."
- "Audit my site and tell me why my blog is not ranking."

## License

MIT. Free to use, modify, and share. See `LICENSE`.
