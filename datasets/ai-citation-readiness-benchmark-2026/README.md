# AI Citation Readiness Benchmark for B2B SaaS

This public dataset supports the Convertos.ai research report:

https://convertos.ai/geo/ai-citation-readiness-benchmark-for-b2b-saas

## Why this dataset exists

Most SaaS teams can answer a familiar SEO question: "Can Google find our pages?"

AI search creates a slightly different question: "Can an answer engine find enough public evidence to describe, compare, and cite our product accurately?"

This benchmark looks at that second question. Convertos.ai reviewed 50 public B2B SaaS websites on June 29, 2026 and checked whether each site exposed basic evidence types that AI answer systems often need:

- a crawlable entity home page
- clear company and product context
- commercial pages such as pricing or plans
- customer proof and use-case evidence
- resources, documentation, trust, security, or compliance pages
- comparison, alternatives, or vs pages that help systems place the product in a market context

The goal is not to rank SaaS companies. The goal is to make a repeatable, lightweight audit pattern that marketers, founders, and SEO/GEO teams can adapt for their own brand visibility work.

## Headline findings

Out of 50 sampled SaaS sites, 46 returned observable homepage HTML during the benchmark fetch.

Among those 46 observable sites:

- 76.1% scored 7 or 8 out of 8.
- Structured data appeared on 65.2%.
- Pricing and about/company signals appeared on 100%.
- Resource, blog, docs, or help content appeared on 97.8%.
- Customer proof appeared on 93.5%.
- Comparison or alternatives coverage was the weakest signal at 45.7%.

The comparison gap is the most actionable finding. Many SaaS sites have strong homepage, pricing, resource, and trust content, but fewer publish fair comparison or alternatives pages. That matters because AI answers frequently need to explain product fit, alternatives, migration paths, and category tradeoffs.

## What the score means

Each observable site could score up to 8 points:

| Field | What it records | Why it matters |
|---|---|---|
| `homepageCrawlable` | Homepage returned useful public HTML | If the entity page cannot be retrieved, it is weaker evidence. |
| `structuredData` | Schema-like markup was observed | Structured data can clarify entity, page, and content context. |
| `pricing` | Pricing or plans page signal | Helps answer commercial-intent questions without guesswork. |
| `about` | About, company, or team page signal | Helps systems verify identity and positioning. |
| `customers` | Customer proof, case study, review, or testimonial signal | Supports claims about real-world use cases. |
| `resources` | Blog, resource hub, guide, or learning center signal | Provides explanatory content beyond homepage copy. |
| `trust` | Security, privacy, trust, compliance, or legal signal | Supports risk-sensitive buyer questions. |
| `compare` | Comparison, alternatives, migration, or vs signal | Helps answer engines place the product in a category map. |

This is intentionally a public-signal score. It does not measure product quality, revenue, market share, brand popularity, paid media, backlinks, or whether a live AI system mentioned a brand in a specific prompt.

## Files

- `saas-citation-readiness-rows.csv` - row-level public observations for the 50-site sample.
- `README.md` - methodology notes, field definitions, findings, and suggested citation.

## Method notes

The crawl checked each homepage plus common public page patterns such as:

- `/pricing`, `/plans`
- `/about`, `/company`, `/team`
- `/customers`, `/case-studies`, `/reviews`
- `/blog`, `/resources`, `/docs`, `/help`, `/support`
- `/security`, `/trust`, `/privacy`, `/legal`, `/compliance`
- `/compare`, `/alternatives`, `/vs`, migration-oriented pages

Primary percentages use the 46 sites that returned crawlable homepage HTML to the benchmark fetch. Four sites returned 403, edge-protection, or app-shell-only responses during the test. Those were recorded as access observations, not as proof that a company lacks a page or signal.

Because this benchmark uses observable public pages, it should be treated as a directional audit, not a definitive company evaluation. A false negative can happen when a page exists under an uncommon URL pattern, requires client-side rendering, blocks automated access, or uses wording that the path-based checks did not capture.

## How teams can reuse this

You can adapt the same rubric for your own SaaS site:

1. List the prompts buyers might ask in AI tools: category discovery, alternatives, pricing, integrations, implementation, security, migration, and comparison.
2. Map each prompt to the public page that should support the answer.
3. Check whether those pages return useful public HTML.
4. Check whether the page states the product, audience, use case, proof, limitations, and update context clearly enough to survive summarization.
5. Track which first-party and third-party URLs appear as cited sources in live AI answers.
6. Fix gaps with useful pages, not thin directory-style listings.

## Suggested citation

Convertos.ai. "AI Citation Readiness Benchmark for B2B SaaS." June 29, 2026. https://convertos.ai/geo/ai-citation-readiness-benchmark-for-b2b-saas

## License

Suggested license: CC BY 4.0 for the dataset and README, unless a more restrictive license is preferred.
