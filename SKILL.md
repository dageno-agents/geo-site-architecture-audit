---
name: geo-site-architecture-audit
description: >
  Audit a real customer website's business, sitemap, navigation, landing pages,
  pricing/account pages, help center, trust/legal pages, regional architecture,
  and external search context before making GEO/AEO/AI-search recommendations.
  Use for mature SEO sites, buyer-decision mapping, missing or fragmented page
  diagnosis, site evidence architecture, and executive talk tracks. Do not use
  for generic content calendars, offsite-only PR plans, or backlink-only audits.
---

# GEO Site Architecture Audit

Use this skill when the task is to analyze a real customer website and recommend how its existing site architecture should be optimized for GEO.

The core rule:

> Do not start from generic content distribution advice. First understand the business and existing website architecture from crawl and search evidence, then recommend how the site should become more AI-citable, comparable, and recommendation-ready.

## Required Inputs

Infer what you can:

- target domain or URL
- target region and language
- whether the user needs an executive talk track, implementation roadmap, or both
- whether the business is regulated or high-trust
- whether the site has multiple domains, subdomains, language paths, help centers, app links, docs, or login flows

If the user gives only a URL, proceed.

## Workflow

1. **Normalize target**
   - Identify canonical domain, region path, language path, redirects, and major subdomains.
   - Note if crawl is blocked, redirected, Cloudflare-gated, or JS-heavy.
   - Preserve uncertainty instead of pretending the crawl is complete.

2. **Crawl site architecture**
   - Inspect homepage, primary nav, footer nav, sitemap, robots, and high-value internal links.
   - Prioritize product/service pages, pricing/plan/account pages, trust/legal pages, support/help center, docs, academy/blog/resources, comparison pages, and conversion pages.
   - Read `references/crawl-checklist.md` when planning crawl coverage.

3. **Search external context**
   - Search brand/category/competitor/review/pricing/trust/community queries.
   - Use search to validate business category, buyer language, competitor set, and third-party sources AI may trust.
   - Do not rely only on the homepage for business interpretation.

4. **Build business profile**
   - Summarize business model, products/services, target users, conversion path, decision criteria, competitors, and high-value jobs-to-be-done.
   - For mature sites, explicitly state when the SEO foundation is strong.

5. **Map pages to GEO scenarios**
   - Map existing pages to buyer questions: selection, pricing, comparison, trust, risk, setup, integration, use case, and conversion.
   - Identify whether each page is citation-ready, fragmented, missing, too generic, too promotional, or not structured enough.
   - Read `references/geo-page-patterns.md` for page-type patterns.
   - Read `references/evidence-schema.md` before turning observations into recommendations.

6. **Diagnose gaps**
   - Distinguish:
     - missing page
     - existing but not structured
     - information fragmented across pages
     - missing comparison/alternative content
     - weak trust/compliance proof
     - weak localization or inconsistent region routing
     - education content that does not connect to conversion

7. **Produce output**
   - Default to a concise executive talk track when the user is preparing for a boss/client meeting.
   - Include P0/P1/P2 site optimization priorities.
   - Recommend concrete page modules, internal links, FAQ/schema opportunities, and missing sections.
   - Read `references/output-templates.md` before drafting.
   - Use `references/recommendation-schema.md` for evidence-bound recommendations.
   - Use `references/scoring-rubric.md` when assigning P0/P1/P2.
   - Use `references/search-context-queries.md` when planning external search and query fan-out checks.
   - For regulated categories, read `references/regulated-industries.md`.

## Output Principles

- Start with current situation, not abstract GEO concepts.
- Acknowledge strong SEO foundations when present.
- Translate GEO into buyer-decision language: "AI can see it, cite it, compare it, and recommend it."
- Make recommendations page-structure specific: comparison pages, pricing explanations, trust centers, FAQ blocks, internal links, schema, localized pages.
- Bind material recommendations to evidence: observed URL, fact, gap type, priority, and confidence.
- Do not recommend GEO hacks by default.
- Treat GEO as buyer-decision evidence architecture built on crawlable, useful, well-structured SEO assets.
- Recommend schema only when it matches visible page content and supports normal search/rich-result eligibility.
- Do not present `llms.txt`, special AI markup, or exact-query page multiplication as required for Google AI visibility.
- Avoid claiming guaranteed AI ranking or financial/medical/legal outcomes.
- If crawl was partially blocked, state the limitation and use available pages/search evidence.

## Default Executive Structure

Use this shape unless the user asks for a full report:

```markdown
## 1. Current Situation
They do / do not already have strong SEO and site architecture.

## 2. GEO Problem
The issue is not just content volume; it is whether AI can cite and recommend the site in buyer questions.

## 3. Business-Specific Decision Questions
List the questions real users ask before choosing, buying, registering, booking, or contacting.

## 4. Site Architecture Opportunities
Map existing pages to P0/P1/P2 improvements.

## 5. Missing Or Weak Sections
Name concrete missing page types or modules.

## 6. Executive Talk Track
Provide a short version the user can say aloud.
```

## Reference Files

- `references/crawl-checklist.md`: crawl targets and evidence capture checklist.
- `references/evidence-schema.md`: minimum evidence fields for site observations.
- `references/recommendation-schema.md`: required fields for evidence-bound recommendations.
- `references/scoring-rubric.md`: public P0/P1/P2 prioritization rubric.
- `references/search-context-queries.md`: query fan-out and external search planning patterns.
- `references/geo-page-patterns.md`: how common page types become GEO assets.
- `references/output-templates.md`: concise executive and implementation templates.
- `references/regulated-industries.md`: special handling for finance, medical, legal, insurance, and other high-trust sites.
