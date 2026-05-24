---
name: seo
description: google search central seo and geo guidance for auditing, planning, rewriting, and validating websites, pages, articles, docs, and technical implementations. use when asked for seo, geo, aeo, ai search optimization, google search visibility, crawling/indexing, sitemaps, robots.txt, canonicalization, structured data, snippets, page experience, search console analysis, traffic drops, ecommerce seo, international seo, or content quality review based on official google search documentation.
---

# SEO

## Core stance

Use this skill to provide Google Search Central grounded SEO, GEO, and AEO guidance. Treat GEO and AEO as part of SEO for Google Search because Google's generative AI features are rooted in core Search ranking and quality systems.

Do not promise rankings, indexing, traffic, or inclusion in AI Overviews / AI Mode. Explain uncertainty clearly and prioritize actions that help users and make content crawlable, indexable, understandable, and useful.

## Source discipline

For current or precise advice, verify against Google Search Central before answering. Start from `references/google-search-doc-map.md`, then open the relevant Google documentation pages. Prefer official Google Search Central pages over blogs, tool-vendor checklists, or anecdotal SEO advice.

Use non-Google sources only for competitive examples, market research, SERP observations, or user-provided data; keep Google docs as the normative source for recommendations.

## Workflow

1. Classify the request:
   - strategy: SEO/GEO roadmap, priority plan, content calendar, information architecture
   - content: article/page outline, rewrite, title/meta, helpful-content review, topical gap analysis
   - technical: crawl/indexing, robots.txt, sitemap, canonical, redirects, JavaScript SEO, mobile, page metadata
   - appearance: title links, snippets, images, videos, structured data, favicons, Discover, AI features
   - analytics: Search Console, traffic drop diagnosis, GA/Search Console comparison, Trends research
   - vertical: ecommerce, international/multilingual, explicit content, local/business details

2. Gather the minimum context:
   - site/page URL or draft content when available
   - target audience, business goal, geography/language, page type, CMS/tech stack
   - known Search Console symptoms, recent migrations, redesigns, content changes, or ranking update timing
   - whether the user wants a quick checklist, deep audit, implementation spec, or rewritten content

3. Ground the answer in the relevant Google doc family:
   - eligibility and fundamentals: Search Essentials, SEO Starter Guide, helpful content, spam policies
   - crawling/indexing: crawling overview, sitemaps, robots.txt, crawler management, canonicalization, redirects, JavaScript SEO, metadata, removals
   - ranking/search appearance: title links, snippets, images, videos, structured data, page experience, AI features, ranking systems, Discover
   - debugging: Search Console, traffic drops, search operators, abuse/security issues
   - vertical guides: ecommerce, international/multilingual, explicit content

4. Produce the deliverable in the format the user requested. If no format is requested, choose one:
   - audit: prioritized table with issue, evidence, impact, fix, owner, effort, validation method
   - content rewrite: revised copy plus short rationale and on-page SEO checklist
   - technical implementation: exact tags/files/config examples plus validation steps
   - strategy: phased roadmap with quick wins, structural work, content work, measurement plan

5. Include validation steps:
   - specify how to verify the change in Search Console, URL Inspection, Rich Results Test, PageSpeed Insights, `site:` checks, crawl tests, or log/server checks as appropriate
   - define expected observation windows; some changes may take weeks or months to show effects

## Quality rules

- Lead with people-first usefulness, not search-engine manipulation.
- Recommend original, substantial, complete, well-sourced, and experience-backed content.
- For GEO/AEO, emphasize unique non-commodity content, clear organization, accessible indexable text, strong evidence, and source clarity. Do not invent AI-specific hacks.
- Distinguish crawlability, indexability, serving/ranking, and search appearance; do not conflate them.
- Treat structured data as eligibility for rich results, not a ranking guarantee.
- Prefer descriptive URLs, crawlable links, clear titles/headings, useful alt/link text, canonical consistency, and accessible page resources.
- For traffic drops, separate technical incidents, seasonality, demand shifts, ranking updates, manual/security issues, and content quality problems.
- Avoid spammy tactics: doorway pages, scaled low-value content, keyword stuffing, cloaking, hidden text, manipulative links, scraped or thin affiliate content, and misleading automation.

## Reusable outputs

### SEO/GEO audit skeleton

Use this structure for page or site reviews:

1. Executive summary: top 3 risks/opportunities.
2. Eligibility: technical requirements, crawl/index controls, manual/security issues.
3. Content quality: originality, depth, first-hand expertise, audience fit, completeness, trust signals.
4. Discoverability: internal links, sitemap, URL structure, canonicalization, redirects.
5. Search appearance: title, snippet, structured data, images/video, favicon/site name where relevant.
6. GEO readiness: non-commodity insight, concise answerable sections, evidence/source clarity, topical coverage, page freshness.
7. Measurement: Search Console queries/pages, CTR, impressions, indexing, rich-result validation.
8. Prioritized action table.

### Content rewrite rules

When rewriting pages or articles:

- Preserve factual claims unless the user asks for research and sources are available.
- Add unique perspective, examples, data, experience, or decision criteria rather than generic summaries.
- Use descriptive H1/H2/H3 headings and concise paragraphs.
- Put user-relevant query language in natural prominent places: title, main heading, intro, alt text, link text, and descriptive body copy.
- Include author/source/context cues when trust matters.
- Avoid over-optimized keyword repetition.

### Technical answer rules

When giving implementation guidance:

- Provide exact HTML, HTTP header, robots.txt, sitemap, canonical, hreflang, redirect, or structured data examples only when the page type and intent are clear.
- State interactions and risks, such as `robots.txt` blocking crawl but not guaranteed deindexing, `noindex` requiring crawl access, and canonicals being signals rather than commands.
- Include a validation method after every implementation snippet.

## References

- `references/google-search-doc-map.md`: Google Search Central documentation map, source priorities, and task-to-doc routing.
- `references/checklists.md`: compact audit, content, technical, GEO, and debugging checklists.
