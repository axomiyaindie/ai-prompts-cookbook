# Prompts Index

All prompts in this cookbook, grouped by category. Each link opens a recipe that follows the standard template in `templates/prompt-template.md`.

## Coding
- [Systematic Code Review](coding/code-review.md) — Senior-engineer style review with severity levels.
- [Refactor Function for Readability](coding/refactor-function.md) — Behavior-preserving cleanup with justification.
- [Generate Unit Tests](coding/write-tests.md) — Framework-specific tests with edge cases.
- [Debug an Error Message](coding/debug-error.md) — Root cause, minimal fix, verification.

## Writing
- [Executive Article Summarizer](writing/summarize-article.md) — Bottom Line + bullets + So What.
- [Rewrite in a Target Tone](writing/rewrite-tone.md) — Tone shift with length and fact constraints.
- [Generate a Structured Outline](writing/generate-outline.md) — Reader-question-driven outline.

## Data
- [Unstructured Text to JSON Extractor](data/extract-json.md) — Schema-based extraction with null handling.
- [Classify Text into Fixed Labels](data/classify-text.md) — Auditable labels with confidence.
- [CSV to Clean Markdown Table](data/csv-to-table.md) — Normalization rules for consistent tables.

## Image Generation
- [Portrait with Cinematic Lighting](image/portrait-lighting.md) — Photography vocabulary for consistent style.
- [Product Shot on Clean Background](image/product-shot.md) — E-commerce style with controlled lighting.

## Adding a New Prompt

1. Copy `../templates/prompt-template.md`.
2. Save it under the correct category folder with a lowercase, hyphenated name.
3. Add a one-line entry to this index.
4. Add a one-line entry to the root README under the matching category.
