# Recommendation Schema

Every material recommendation should include these fields.

```yaml
priority: P0 | P1 | P2
buyer_question:
existing_evidence:
  - url:
    page_type:
    observed_fact:
gap_type: missing | fragmented | weakly_structured | unlocalized | not_citation_ready
recommended_page_or_module:
why_it_matters_for_geo:
business_impact:
implementation_effort: low | medium | high
confidence: high | medium | low
```

## Gap Types

- `missing`: the buyer question has no clear official page.
- `fragmented`: relevant evidence exists across multiple pages but is not connected.
- `weakly_structured`: the content exists but lacks answer-first summaries, tables, FAQs, comparison blocks, or clear headings.
- `unlocalized`: key buyer-decision content is absent or weaker in the target region/language.
- `not_citation_ready`: page is too promotional, too vague, blocked, JS-only, or lacks concrete evidence.

## Quality Bar

A recommendation is strong when it names:

- the buyer question
- the page or module to change
- the evidence that proves the gap
- why AI systems or users need that evidence
- the expected business role without promising guaranteed rankings
