# Agent Guide

Use this guide when executing the skill end to end.

## Execution Sequence

1. Normalize the target URL.
2. Inspect redirects, canonical region/language paths, and obvious subdomains.
3. Crawl homepage, navigation, footer, sitemap, robots, and high-value pages.
4. Search web context for brand, category, competitors, reviews, trust, pricing, and community signals.
5. Build the business profile before making recommendations.
6. Map existing pages to GEO decision scenarios.
7. Diagnose gaps as missing, fragmented, weakly structured, unlocalized, or not citation-ready.
8. Bind each material recommendation to URL evidence, buyer question, gap type, priority, and confidence.
9. Output executive talk track first; implementation roadmap second if needed.

## Evidence To Capture

- URL and page title
- H1/H2/H3 headings
- page purpose
- visible price/plan/account/product facts
- trust/compliance claims
- CTAs and conversion path
- FAQ/help center availability
- internal links to related buyer-decision pages
- external sources and competitor signals

## Decision Rules

- If the site is mature, lead with that strength.
- If pricing/account information exists but is scattered, recommend comparison and cost-explanation pages.
- If trust/legal pages exist but are scattered, recommend a Trust Center or Safety Hub.
- If education content exists but does not link to conversion assets, recommend next-step modules.
- If the site has multiple region/language variants, check whether buyer-critical pages exist in each target language.
- Do not recommend GEO hacks by default; use normal crawlability, helpful content, page structure, internal links, and evidence clarity as the foundation.
- Recommend schema only when it matches visible content and ordinary search eligibility.
- Do not treat `llms.txt` or special AI markup as required for Google AI visibility.

## Fallbacks

- If sitemap is blocked, use navigation, search results, and known path patterns.
- If crawl is blocked by Cloudflare or JavaScript, use browser rendering, search snippets, public indexed pages, and official PDFs where available.
- If external search is weak, lower confidence and avoid definitive competitor claims.
