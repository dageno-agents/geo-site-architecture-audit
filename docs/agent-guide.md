# Agent Guide

Use this guide when executing the skill end to end.

## Execution Sequence

1. Normalize the target URL.
2. Inspect redirects, canonical region/language paths, and obvious subdomains.
3. Choose a crawl preset and page cap.
4. Crawl homepage, navigation, footer, sitemap, robots, and high-value pages.
5. Check robots.txt and crawl access signals for major search and AI user agents when available.
6. Search web context for brand, category, competitors, reviews, trust, pricing, and community signals.
7. Build the business profile before making recommendations.
8. Map existing pages to GEO decision scenarios.
9. Diagnose gaps as missing, fragmented, weakly structured, unlocalized, orphaned, deeply buried, or not citation-ready.
10. Bind each material recommendation to URL evidence, buyer question, gap type, priority, and confidence.
11. Output executive talk track first; implementation roadmap second if needed.

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
- robots and AI/search crawler access signals
- internal link depth or orphan risk for buyer-critical pages
- schema or structured data that supports the visible page content

## Decision Rules

- If the site is mature, lead with that strength.
- If pricing/account information exists but is scattered, recommend comparison and cost-explanation pages.
- If trust/legal pages exist but are scattered, recommend a Trust Center or Safety Hub.
- If education content exists but does not link to conversion assets, recommend next-step modules.
- If the site has multiple region/language variants, check whether buyer-critical pages exist in each target language.
- If a buyer-critical page is more than 3 clicks from core navigation or only reachable through search/sitemap, flag discoverability risk.
- If structured data is present, check whether Organization, Product/Service, Article, FAQ, Breadcrumb, and other visible-content schemas connect cleanly rather than existing as isolated blocks.
- Do not recommend GEO hacks by default; use normal crawlability, helpful content, page structure, internal links, and evidence clarity as the foundation.
- Recommend schema only when it matches visible content and ordinary search eligibility.
- Do not treat `llms.txt` or special AI markup as required for Google AI visibility.

## Fallbacks

- If sitemap is blocked, use navigation, search results, and known path patterns.
- If crawl is blocked by Cloudflare or JavaScript, use browser rendering, search snippets, public indexed pages, and official PDFs where available.
- If external search is weak, lower confidence and avoid definitive competitor claims.
- If robots.txt blocks key AI/search crawlers for priority pages, surface this before content recommendations.
