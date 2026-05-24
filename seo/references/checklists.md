# SEO and GEO checklists

## Universal SEO audit

- Confirm crawl/index eligibility: HTTP 200, accessible HTML, no accidental `noindex`, no unintended robots.txt block, canonical target is correct.
- Check Search Console: indexing status, pages, queries, impressions, CTR, enhancements, manual actions, security issues.
- Inspect internal discoverability: crawlable links, logical directories, important pages in sitemap, orphan-page risk.
- Review page purpose: clear audience, unique value, original experience or analysis, complete answer, trustworthy sourcing.
- Review on-page clarity: descriptive title/H1, useful headings, natural query language, descriptive link text, useful alt text.
- Review search appearance: snippet suitability, structured data eligibility, images/video requirements, favicon/site name where relevant.
- Review page experience holistically; do not reduce quality to a single metric.
- Prioritize fixes by user impact, crawl/index impact, business value, confidence, and implementation effort.

## GEO / AI search readiness

- Treat GEO/AEO as SEO for Google Search, not a separate loophole.
- Make key information accessible as indexable text, not only images, scripts, PDFs, or gated content.
- Add non-commodity value: first-hand examples, data, testing notes, expert judgment, original comparisons, tradeoffs, or case details.
- Organize content into answerable sections with clear headings and concise explanations.
- Make trust visible: author/site context, source links, methodology, dates, evidence, and limitations where relevant.
- Avoid generic AI-generated summaries that restate what already exists online.
- Cover adjacent user intents naturally rather than keyword-stuffing fan-out variants.

## Technical implementation

- robots.txt: use to manage crawling, not as a privacy or deindexing mechanism.
- noindex: ensure Google can crawl the page to see the directive.
- canonical: use consistent signals; avoid canonicalizing to irrelevant or blocked pages.
- sitemaps: include canonical URLs that matter; keep lastmod accurate when used.
- redirects: use permanent redirects for durable moves; preserve relevant content equivalence.
- JavaScript: ensure important content and links appear in rendered output Google can access.
- hreflang: use reciprocal, valid language/region annotations with correct canonicals.
- structured data: match visible page content and follow the exact feature guide.

## Content review

- Does the page provide original information, reporting, research, analysis, or first-hand experience?
- Is the topic covered substantially and completely for the intended audience?
- Does the page add value beyond copying, paraphrasing, or aggregating other sources?
- Are titles/headings descriptive without exaggeration or shock framing?
- Would users bookmark, share, cite, or recommend the page?
- Are sources, expertise, author/site background, and update context clear where trust matters?
- Would the audience leave feeling they achieved their goal?
- Is the content mainly made for people rather than search traffic capture?

## Traffic drop diagnosis

- Segment by page, query, country, device, and search appearance.
- Compare dates against site releases, migrations, robots/canonical/noindex changes, outages, manual/security issues, and known ranking updates.
- Check whether the drop is impressions, CTR, average position, indexed pages, or conversion quality.
- Compare with demand/seasonality using Trends or historical Search Console windows.
- Validate representative URLs with URL Inspection and rendered-page checks.
- Produce hypotheses with evidence, confidence, and next validation step.
