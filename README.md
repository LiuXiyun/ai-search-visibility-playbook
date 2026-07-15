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

## Goal 200 AI visibility resource batch

- [AI Search Category Prompt Library](./ai-search-category-prompt-library.md)
- [AI Recommendation Risk Register](./ai-recommendation-risk-register.md)
- [Citation Source Owner Map](./citation-source-owner-map.md)
- [AI Answer Product Fit Checklist](./ai-answer-product-fit-checklist.md)
- [GEO Landing Page Evidence Plan](./geo-landing-page-evidence-plan.md)
- [AI Visibility Prompt Review Board](./ai-visibility-prompt-review-board.md)
- [Answer Engine Claim Verification Table](./answer-engine-claim-verification-table.md)
- [LLM Citation Recheck Calendar](./llm-citation-recheck-calendar.md)
- [AI Search Source Priority Score](./ai-search-source-priority-score.md)
- [SaaS Comparison Evidence Template](./saas-comparison-evidence-template.md)
- [AI Tool Profile Quality Brief](./ai-tool-profile-quality-brief.md)
- [AI Visibility Monthly Board Pack](./ai-visibility-monthly-board-pack.md)
- [Answer Engine Procurement Evidence Checklist](./answer-engine-procurement-evidence-checklist.md)
- [AI Search Migration Page Brief](./ai-search-migration-page-brief.md)
- [AI Visibility Sales Enablement Map](./ai-visibility-sales-enablement-map.md)
- [Prompt Monitoring Sample Size Notes](./prompt-monitoring-sample-size-notes.md)
- [GEO Entity Homepage Audit](./geo-entity-homepage-audit.md)
- [AI Answer Citation Cleanup Queue](./ai-answer-citation-cleanup-queue.md)
- [AI Overview Owned Source Gap Log](./ai-overview-owned-source-gap-log.md)
- [Answer Engine Review Site Brief](./answer-engine-review-site-brief.md)
- [AI Visibility SEO Handoff Template](./ai-visibility-seo-handoff-template.md)
- [GEO Editorial Calendar from Prompts](./geo-editorial-calendar-from-prompts.md)
- [AI Answer Misclassification Audit](./ai-answer-misclassification-audit.md)
- [AI Search Partner Mention Tracker](./ai-search-partner-mention-tracker.md)
- [Citation-Ready Case Study Template](./citation-ready-case-study-template.md)
- [AI Search Pricing Answer Checklist](./ai-search-pricing-answer-checklist.md)
- [LLM Citation Technical Access Check](./llm-citation-technical-access-check.md)
- [GEO FAQ Source Map](./geo-faq-source-map.md)
- [AI Visibility Localization Review](./ai-visibility-localization-review.md)
- [AI Answer Evidence Sprint Retro](./ai-answer-evidence-sprint-retro.md)
- [AI Search Use-Case Proof Matrix](./ai-search-use-case-proof-matrix.md)
- [Third-Party Listing Refresh Calendar](./third-party-listing-refresh-calendar.md)
- [AI Visibility Content Decay Watchlist](./ai-visibility-content-decay-watchlist.md)
- [Answer Engine Integrations Page Brief](./answer-engine-integrations-page-brief.md)
- [AI Search Competitor Source Swap Log](./ai-search-competitor-source-swap-log.md)
- [GEO Proof Page Internal Link Map](./geo-proof-page-internal-link-map.md)
- [AI Visibility Demo Script from Prompts](./ai-visibility-demo-script-from-prompts.md)
- [LLM Answer Evidence Acceptance Criteria](./llm-answer-evidence-acceptance-criteria.md)
- [AI Search Release Note Monitoring](./ai-search-release-note-monitoring.md)
- [Citation Readiness Roadmap for Founders](./citation-readiness-roadmap-for-founders.md)

## Goal 200 follow-up resource batch

- [AI Search Category Entry Page Brief](./ai-search-category-entry-page-brief.md)
- [AI Answer Feature Claim Audit](./ai-answer-feature-claim-audit.md)
- [GEO Proof-Led Content Outline](./geo-proof-led-content-outline.md)
- [AI Citation Owner RACI](./ai-citation-owner-raci.md)
- [Answer Engine Integration Proof Map](./answer-engine-integration-proof-map.md)
- [AI Visibility Source Risk Table](./ai-visibility-source-risk-table.md)
- [GEO Refresh Acceptance Checklist](./geo-refresh-acceptance-checklist.md)
- [AI Search Use-Case Evidence Bank](./ai-search-use-case-evidence-bank.md)
- [LLM Citation Message House](./llm-citation-message-house.md)
- [AI Answer Comparison Gap Review](./ai-answer-comparison-gap-review.md)
- [GEO Source Trust Tiering](./geo-source-trust-tiering.md)
- [AI Search Demo Prompt Pack](./ai-search-demo-prompt-pack.md)
- [Citation-Ready About Page Audit](./citation-ready-about-page-audit.md)
- [AI Visibility Competitor Proof Audit](./ai-visibility-competitor-proof-audit.md)
- [Answer Engine Landing Page Source Map](./answer-engine-landing-page-source-map.md)
- [GEO Customer Proof Freshness Check](./geo-customer-proof-freshness-check.md)
- [AI Search Category Definition Template](./ai-search-category-definition-template.md)
- [LLM Answer Red-Team Prompts](./llm-answer-red-team-prompts.md)
- [AI Visibility Support Source Audit](./ai-visibility-support-source-audit.md)
- [GEO Review Site Profile Brief](./geo-review-site-profile-brief.md)
- [AI Answer Trust Signal Map](./ai-answer-trust-signal-map.md)
- [Prompt Intent to Page Map](./prompt-intent-to-page-map.md)
- [AI Visibility Quarterly Retro](./ai-visibility-quarterly-retro.md)
- [Answer Engine Market Map Notes](./answer-engine-market-map-notes.md)
- [GEO Owned Source Readiness Score](./geo-owned-source-readiness-score.md)
- [AI Citation Priority Queue](./ai-citation-priority-queue.md)
- [LLM Source Duplication Review](./llm-source-duplication-review.md)
- [AI Answer Procurement Question Bank](./ai-answer-procurement-question-bank.md)
- [GEO Content Brief Proof Table](./geo-content-brief-proof-table.md)
- [AI Search Citation Before-After Card](./ai-search-citation-before-after-card.md)
- [Answer Engine Category Fit Review](./answer-engine-category-fit-review.md)
- [AI Visibility Missing Source Playbook](./ai-visibility-missing-source-playbook.md)
- [GEO AI Tool Listing Field Guide](./geo-ai-tool-listing-field-guide.md)
- [AI Search Incorrect Claim Workflow](./ai-search-incorrect-claim-workflow.md)
- [Citation-Ready Security Page Template](./citation-ready-security-page-template.md)
- [AI Answer Persona Prompt Map](./ai-answer-persona-prompt-map.md)
- [GEO Case Study Source Checklist](./geo-case-study-source-checklist.md)
- [AI Visibility Partner Source Brief](./ai-visibility-partner-source-brief.md)
- [LLM Citation Issue Taxonomy](./llm-citation-issue-taxonomy.md)
- [AI Search Noindex and Rendering Review](./ai-search-noindex-and-rendering-review.md)
- [Answer Engine Feature Evidence Matrix](./answer-engine-feature-evidence-matrix.md)
- [GEO Report Actionability Scorecard](./geo-report-actionability-scorecard.md)
- [AI Visibility Competitive Narrative Audit](./ai-visibility-competitive-narrative-audit.md)
- [Citation-Ready Pricing FAQ Outline](./citation-ready-pricing-faq-outline.md)
- [AI Answer Source Replacement Log](./ai-answer-source-replacement-log.md)
- [GEO Podcast and Interview Source Plan](./geo-podcast-and-interview-source-plan.md)
- [AI Search Review Page Monitor](./ai-search-review-page-monitor.md)
- [LLM Answer Entity Consistency Test](./llm-answer-entity-consistency-test.md)
- [AI Visibility Source Backlog Grooming](./ai-visibility-source-backlog-grooming.md)
- [GEO Field Evidence Collection Form](./geo-field-evidence-collection-form.md)
- [AI Search Customer Objection Prompt List](./ai-search-customer-objection-prompt-list.md)
- [Answer Engine Implementation Page Brief](./answer-engine-implementation-page-brief.md)
- [GEO Ecosystem Source Map](./geo-ecosystem-source-map.md)
- [AI Visibility Experiment Design Sheet](./ai-visibility-experiment-design-sheet.md)
- [Citation-Ready Alternatives Page Rubric](./citation-ready-alternatives-page-rubric.md)
- [AI Answer Change Log Template](./ai-answer-change-log-template.md)
- [GEO Source Coverage Heatmap](./geo-source-coverage-heatmap.md)
- [AI Search Integrations Prompt Set](./ai-search-integrations-prompt-set.md)
- [LLM Citation Remediation SLA](./llm-citation-remediation-sla.md)
- [AI Visibility Founder Dashboard Notes](./ai-visibility-founder-dashboard-notes.md)


## 2026-07-15 source-quality resource batch

- [AI Answer Buyer Objection Map](./ai-answer-buyer-objection-map.md)
- [AI Search Source Freshness SLA](./ai-search-source-freshness-sla.md)
- [GEO Comparison Page Evidence Check](./geo-comparison-page-evidence-check.md)
- [LLM Citation Editorial Brief](./llm-citation-editorial-brief.md)
- [AI Visibility Founder Weekly Review](./ai-visibility-founder-weekly-review.md)
- [Answer Engine Third-Party Proof Plan](./answer-engine-third-party-proof-plan.md)
- [AI Search Pricing Source Map](./ai-search-pricing-source-map.md)
- [GEO Security Trust Page Checklist](./geo-security-trust-page-checklist.md)
- [AI Answer Incorrect Feature Fix Log](./ai-answer-incorrect-feature-fix-log.md)
- [AI Visibility Partner Mention Audit](./ai-visibility-partner-mention-audit.md)
- [Answer Engine Demo Page Brief](./answer-engine-demo-page-brief.md)
- [AI Search Category Gap Retro](./ai-search-category-gap-retro.md)
- [GEO Docs and Help Center Scorecard](./geo-docs-and-help-center-scorecard.md)
- [AI Citation Public Proof Backlog](./ai-citation-public-proof-backlog.md)
- [LLM Answer Competitive Claim Check](./llm-answer-competitive-claim-check.md)
- [AI Search Review Response Playbook](./ai-search-review-response-playbook.md)
- [GEO Product Launch Source Plan](./geo-product-launch-source-plan.md)
- [AI Visibility Agency Audit Scope](./ai-visibility-agency-audit-scope.md)
- [Answer Engine Evidence-Led FAQ Plan](./answer-engine-evidence-led-faq-plan.md)
- [AI Search Trust Signal Regression Log](./ai-search-trust-signal-regression-log.md)

