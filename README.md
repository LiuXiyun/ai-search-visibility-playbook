# AI Search Visibility Playbook

A practical playbook for auditing whether a brand is visible, accurately described, and cited across AI answer engines such as ChatGPT, Perplexity, Gemini, Google AI, Claude, and Copilot.

This repository is maintained as a public resource for SEO, growth, content, and RevOps teams working on GEO, AEO, AI visibility, and answer-engine reporting.

For automated monitoring across prompts, answer engines, competitors, and cited sources, see [Convertos.ai](https://convertos.ai/).

## Who this is for

- SEO teams moving beyond classic rank tracking
- Growth teams that need AI-search-aware reporting
- SaaS founders checking whether answer engines understand their category
- Content teams building pages that can be cited by AI systems
- Agencies reporting GEO, AEO, and LLM visibility to clients

## Core idea

Traditional SEO asks: where does our page rank?

AI visibility asks a different set of questions:

- Does the model mention the brand when buyers ask category questions?
- Does the model describe the product accurately?
- Which sources does the model cite or rely on?
- Which competitors appear more often?
- Which prompts trigger recommendations, comparisons, or omissions?
- Which owned and third-party pages need to be improved?

## Audit workflow

### 1. Build a prompt inventory

Do not only test brand prompts. Include the way buyers ask before they know your brand.

| Prompt type | Example |
| --- | --- |
| Brand | What is Convertos.ai? |
| Category | Best AI visibility monitoring tools |
| Problem | How do I track whether ChatGPT recommends my brand? |
| Comparison | GEO monitoring vs rank tracking |
| Persona | AI visibility workflow for a SaaS SEO team |
| Evaluation | Which tools monitor Perplexity and Gemini citations? |

### 2. Capture answers consistently

For each answer, store:

- Exact prompt
- Answer engine and model, if visible
- Date and location assumptions
- Brand presence
- Brand position
- Competitor mentions
- Cited URLs
- Incorrect or missing claims
- Follow-up prompt behavior

### 3. Score visibility

A simple scorecard is often enough to start.

| Score | Meaning |
| --- | --- |
| 0 | Brand absent |
| 1 | Brand mentioned but not recommended |
| 2 | Brand listed with weak or inaccurate detail |
| 3 | Brand listed with accurate category fit |
| 4 | Brand recommended with useful detail |
| 5 | Brand recommended and cited from strong sources |

### 4. Diagnose source gaps

If the brand is missing, the cause is usually one of these:

- The category is not clearly stated on owned pages.
- Third-party coverage is too thin or inaccurate.
- Comparison and use-case pages are missing.
- Important pages are not crawlable or are too script-dependent.
- Competitors have more direct answers for the same buyer intent.
- The brand has listings, but the descriptions are one-line and not useful.

### 5. Improve pages that models can understand

Useful AI-search pages usually include:

- A direct definition in the first screen
- Product category and audience
- Concrete workflows
- Supported engines or channels
- Methodology and measurement cadence
- Clear examples
- FAQ sections with concise answers
- Internal links to pricing, docs, product, and comparison pages
- External validation from credible directories, reviews, interviews, or reports

## Weekly operating cadence

1. Run the prompt set.
2. Save answer text and cited URLs.
3. Compare brand presence by answer engine.
4. Identify prompts where competitors gained visibility.
5. Review whether citations came from owned pages or third-party pages.
6. Update content only where a visibility gap is tied to a source gap.
7. Track whether the next crawl or model answer changes.

## Backlink quality notes

Not every backlink helps AI visibility. A useful external page should explain the product, place it in the right category, and link to the official site.

Good external pages:

- Use the product name consistently
- Link directly to the official domain
- Describe the real audience and use cases
- Appear on a crawlable public URL
- Avoid forced reciprocal link schemes
- Avoid generic one-line descriptions

Thin external pages may still be indexed, but they rarely help answer engines understand the product.

## Example reporting table

| Engine | Prompt group | Presence | Position | Cited source | Action |
| --- | --- | --- | --- | --- | --- |
| ChatGPT | Category | Mentioned | Top 3 | Owned use-case page | Improve comparison detail |
| Perplexity | Problem | Absent | N/A | Competitor blog | Add workflow page |
| Gemini | Brand | Mentioned | First | Homepage | Fix outdated phrasing |
| Google AI | Evaluation | Mentioned | Later | Directory page | Earn stronger third-party source |

## Research datasets

- [AI Citation Readiness Benchmark for B2B SaaS](datasets/ai-citation-readiness-benchmark-2026/) - a public Convertos.ai dataset covering 50 B2B SaaS websites and the observable evidence signals that may help answer engines describe, compare, and cite a SaaS brand accurately.

## Related resources

- [Convertos.ai](https://convertos.ai/) - AI visibility monitoring for GEO, AEO, and SEO teams
- Prompt inventory templates
- Citation audit worksheets
- GEO content brief templates
- AI search reporting scorecards

## License

This playbook is provided as a public reference. Use it to structure internal audits, client reporting, and content planning.
