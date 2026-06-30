# Security

## Sensitive Data

Do not commit:

- API keys
- cookies
- bearer tokens
- customer crawl exports
- logged-in screenshots
- private Dageno exports
- private sales notes
- personally identifiable information

## Crawling

- Respect robots.txt where available.
- Prefer shallow, targeted crawling over broad scraping.
- Do not bypass login, paywalls, or access controls.
- If Cloudflare or bot checks block access, state the limitation and use public search/indexed evidence.

## Reporting

- Do not expose secrets in reports.
- For regulated industries, avoid claims of guaranteed investment, medical, legal, or compliance outcomes.
- Treat third-party reviews and community posts as reputation evidence, not authoritative proof.

## Public Repository Boundary

This repository should contain workflow, schemas, templates, and safety guidance only.

Customer-specific artifacts belong in private workspaces or deliverables.
