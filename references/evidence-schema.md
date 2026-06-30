# Evidence Schema

Use this schema to keep audits evidence-bound.

## Site Observation

```yaml
url:
effective_url:
page_type:
title:
h1:
key_headings:
observed_facts:
  - fact:
    evidence_text:
    page_location:
business_role:
geo_role:
conversion_role:
internal_links:
crawl_status: complete | partial | blocked | redirected | inferred_from_search
confidence: high | medium | low
```

## External Signal

```yaml
source_url:
source_type: official | competitor | review | community | media | directory | regulator | documentation
query_used:
observed_fact:
brands_or_competitors_mentioned:
buyer_question_supported:
confidence: high | medium | low
```

## Rules

- Do not turn an unsupported inference into a fact.
- If a page is blocked, mark `crawl_status` and use search/indexed evidence with lower confidence.
- Capture exact URLs for the pages that justify P0/P1 recommendations.
- For regulated categories, separate official/regulatory evidence from community reputation evidence.
