---
name: seo-content-optimizer
description: End-to-end SEO and content engine for any website, blog, or landing page. Use this skill whenever the user wants to do keyword research, optimize on-page SEO (titles, meta descriptions, headings, URLs, alt text, internal links), write or rewrite SEO blog posts and articles, audit a site's technical SEO and content gaps, improve rankings, target featured snippets or AI Overviews (AEO), or plan a content calendar. Trigger on phrases like "optimize this page", "write a blog post about", "do keyword research", "SEO audit", "why isn't this ranking", "improve my meta description", "rewrite this for SEO", "content plan", "find keywords for", "fix my internal linking", or any mention of search rankings, organic traffic, SERPs, or on-page SEO, even if the user does not say the word "SEO" explicitly. Platform-agnostic: works for WordPress, Wix, Shopify, Webflow, custom sites, or plain HTML.
---

# SEO Content Optimizer

A general-purpose system for ranking websites and writing content that earns organic traffic. It covers the four jobs that move rankings: finding the right keywords, optimizing pages on-page, writing genuinely useful content, and auditing for technical and content issues.

The goal is always the same: help a real reader, then make that help easy for search engines and AI answer engines to find, understand, and trust. Tactics that fight that goal (keyword stuffing, thin content, manipulative links) win short-term and lose long-term, so this skill never reaches for them.

## How to use this skill

First, figure out which of the four jobs the user needs. They often need more than one, in this order:

1. **Keyword research** when the user does not yet know what to target, or asks "what should I write about" / "find keywords". See `references/keyword-research.md`.
2. **Content writing** when they want a blog post, article, landing page, or product copy drafted or rewritten. See `references/content-writing.md`.
3. **On-page optimization** when they have a page (or draft) and want the title, meta, headings, URL, alt text, and links tuned. See `references/on-page-seo.md`.
4. **Technical and content audit** when they want to know what is wrong with a site or why something is not ranking. See `references/technical-audit.md`.

Read the relevant reference file before doing the work. Each one is a focused playbook with checklists, formulas, and examples. Do not try to hold all four in your head at once; load what the task needs.

## Before you start: gather context

Good SEO output depends on context that the user usually has but does not volunteer. Ask for whatever is missing and matters, but keep it to a few questions, never an interrogation:

- **The site and niche.** What does the business do, who is the audience, what makes it different? This shapes intent and angle.
- **The target page or topic.** A URL, a draft, or a working title.
- **The primary keyword or goal**, if they have one. If not, that is the keyword-research job.
- **Geography and language**, when local or regional intent matters (a plumber in Ottawa is not competing with one in Sydney).
- **Brand voice constraints**, if any. Match the site's existing tone.

If you have web access, look at the live page or competing pages rather than guessing. Real SERP data beats assumptions every time.

## Operating principles

These hold across all four jobs:

**Search intent comes first.** Every query has an intent: informational, commercial, transactional, or navigational. A page that satisfies the wrong intent will not rank no matter how optimized it is. Before optimizing or writing anything, decide what the searcher actually wants and build to that.

**Write for the person, format for the machine.** The content has to be the best answer a reader could get. Then structure it (headings, short paragraphs, lists where they fit, schema where relevant) so crawlers and AI answer engines can parse it. Never sacrifice readability for a keyword count.

**One primary keyword per page, plus a cluster.** Each page targets one main keyword and a handful of closely related secondary terms and questions. Spreading one page across unrelated keywords, or targeting the same keyword with multiple pages (cannibalization), both dilute rankings.

**Match or beat what already ranks.** The pages on page one are a live answer key for what Google rewards for that query: the depth, the format, the angle, the content type. Read them before you write. Aim to cover everything they cover and add something they miss.

**E-E-A-T is the trust layer.** Experience, Expertise, Authoritativeness, Trustworthiness. Show real first-hand experience, cite credible sources, make authorship and the business clear, and keep facts accurate. This matters more every year, especially for YMYL (your money or your life) topics like health and finance.

**Optimize for AI answer engines too (AEO).** Google's AI Overviews, ChatGPT, and Perplexity increasingly answer queries directly. To be cited, give a crisp, self-contained answer near the top of the page (40 to 60 words), use clear question-style headings, and add structured data. `references/technical-audit.md` and `references/content-writing.md` cover the specifics.

## Output expectations

Deliver work the user can act on immediately, not vague advice:

- When optimizing on-page, give the exact strings to paste (title tag, meta description, H1, slug) with character counts, not "make your title better".
- When writing content, deliver the full draft, formatted, with the primary keyword placement already handled and internal-link suggestions noted inline.
- When auditing, give a prioritized list (highest impact and lowest effort first), with the specific fix for each item, not a generic checklist.
- When doing keyword research, give a table the user can sort and decide from: keyword, rough intent, why it is worth targeting, and a suggested page type.

For substantial deliverables (a full blog post, a complete audit, a keyword map), save a file (markdown by default) so the user can keep and edit it. For quick single-element fixes (one meta description), just give it inline.

## What to avoid

Steer the user away from tactics that carry real risk: buying links, spinning or AI-mass-producing thin pages, hidden text, exact-match anchor spam, doorway pages, and faking reviews or expertise. If a user asks for these, explain the risk plainly and offer the legitimate version of what they are trying to achieve. Rankings built on tricks evaporate at the next algorithm update; rankings built on genuine usefulness compound.
