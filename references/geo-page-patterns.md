# GEO Page Patterns

Use these patterns to convert site architecture into GEO recommendations.

## Product / Service Pages

GEO purpose:

- Help AI answer "what can I use this for?"
- Connect category, use case, buyer, risks, and next action.

Recommended modules:

- plain-language summary
- best-fit user or scenario
- product/service facts table
- supported workflows or markets
- limitations and risks
- related pricing/account/plan links
- FAQ block
- schema where appropriate

## Pricing / Account / Plan Pages

GEO purpose:

- Help AI answer "which plan/account is right for me?"
- Support recommendation and comparison answers.

Recommended modules:

- plan/account comparison table
- total cost explanation
- example cost scenarios
- best-fit user per plan
- limits, fees, exclusions, and risk notes
- FAQ block
- internal links to product and support pages

## Trust / Safety / Compliance Pages

GEO purpose:

- Help AI decide whether it can safely recommend the brand.

Recommended modules:

- centralized Trust Center or Safety Hub
- regulatory or certification evidence
- data/security/fund/customer protection claims
- complaint/support/escalation path
- legal documents
- third-party reviews or proof
- restricted regions or limitations

Entity consistency checks:

- Organization identity and sameAs links align with official social/profile pages.
- Regulatory, license, or certification claims link to official sources where possible.
- Legal, privacy, complaint, support, and contact pages are internally connected.
- Structured data, if present, matches visible content and uses stable entity references.

## Platform / Tool / Integration Pages

GEO purpose:

- Help AI answer "which tool or integration should I use?"

Recommended modules:

- supported platforms and use cases
- setup steps
- compatibility table
- user-fit matrix
- troubleshooting FAQ
- links to pricing/account/product pages

## Education / Blog / Academy Pages

GEO purpose:

- Capture early-stage AI answers and route users to decision assets.

Recommended modules:

- answer-first summary
- glossary/definition structure
- risk and limitation explanation
- "next step" links to products, pricing, demo, or contact
- related buyer questions
- author/update metadata where relevant

## Structured Data And Entity Graph

GEO purpose:

- Help search systems and downstream AI surfaces understand page entities, not create unsupported claims.

Recommended checks:

- Organization, Product/Service, Article, FAQ, Breadcrumb, Review, LocalBusiness, or FinancialService schema is used only when it matches visible page content.
- Entity identifiers are stable across page templates.
- sameAs/profile links point to official and consistent external profiles.
- FAQ schema matches visible FAQ blocks.
- Breadcrumb schema matches visible site hierarchy.
- Avoid isolated schema blocks that contradict the page, hide claims, or create entity confusion.

## Comparison / Alternatives Pages

GEO purpose:

- Help AI include the brand in "best", "vs", and "alternatives" answers.

Recommended modules:

- neutral comparison criteria
- who each option is best for
- pricing/cost comparison
- risk/trust comparison
- feature/platform comparison
- clear limitations and fair caveats
