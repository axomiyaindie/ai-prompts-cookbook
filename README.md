# AI Prompts Cookbook

A curated collection of battle-tested prompt recipes for AI tools, organized by platform and use case.

Unlike random prompt dumps, every recipe follows a consistent template: the prompt, an example input, and a note on why it works.

## Table of Contents

- [Structure](#structure)
- [How to Use](#how-to-use)
- [Prompts by Category](#prompts-by-category)
  - [Coding](#coding)
  - [Writing](#writing)
  - [Data](#data)
  - [Image Generation](#image-generation)
  - [Platform](#platform)
- [Patterns](#patterns)
- [Contributing](#contributing)
- [License](#license)

## Structure

```text
.
├── prompts/          Ready-to-use prompts by category
│   ├── coding/
│   ├── writing/
│   ├── data/
│   ├── image/
│   └── platform/
├── patterns/         Reusable techniques behind reliable prompts
├── templates/        The blank recipe template used for contributions
├── CONTRIBUTING.md   Contribution guidelines
└── LICENSE           MIT license
```

## How to Use

1. Browse to the relevant category below.
2. Open the prompt file.
3. Copy the prompt.
4. Replace the `{{PLACEHOLDERS}}` with your own content.
5. Paste into your AI tool (ChatGPT, Claude, Cursor, Midjourney, etc.).

## Prompts by Category

### Coding

- [Systematic Code Review](prompts/coding/code-review.md) — Thorough, security-focused review of a code snippet.
- [Refactor Function for Readability](prompts/coding/refactor-function.md) — Behavior-preserving cleanup with justification.
- [Generate Unit Tests](prompts/coding/write-tests.md) — Framework-specific tests with edge cases.
- [Debug an Error Message](prompts/coding/debug-error.md) — Root cause, minimal fix, verification.
- [Natural Language to SQL Query](prompts/coding/sql-query.md) — Schema-constrained SQL generation.
- [REST Endpoint Design](prompts/coding/api-design.md) — Request/response schemas with error cases.

### Writing

- [Executive Article Summarizer](prompts/writing/summarize-article.md) — Turn a long article into a concise, actionable summary.
- [Rewrite in a Target Tone](prompts/writing/rewrite-tone.md) — Tone shift with length and fact constraints.
- [Generate a Structured Outline](prompts/writing/generate-outline.md) — Reader-question-driven outline.
- [Short Personalized Cold Email](prompts/writing/cold-email.md) — Concrete personalization under 120 words.
- [Meeting Transcript to Decisions and Actions](prompts/writing/meeting-notes.md) — Decisions, owners, open questions.

### Data

- [Unstructured Text to JSON Extractor](prompts/data/extract-json.md) — Convert messy text into clean, structured JSON.
- [Classify Text into Fixed Labels](prompts/data/classify-text.md) — Auditable labels with confidence scores.
- [CSV to Clean Markdown Table](prompts/data/csv-to-table.md) — Normalization rules for consistent tables.
- [Named Entity Extraction to JSON](prompts/data/extract-entities.md) — People, orgs, locations, dates.

### Image Generation

- [Portrait with Cinematic Lighting](prompts/image/portrait-lighting.md) — Photography vocabulary for consistent style.
- [Product Shot on Clean Background](prompts/image/product-shot.md) — E-commerce style with controlled lighting.
- [Landscape Scene with Defined Mood](prompts/image/landscape-scene.md) — Time, weather, and mood pinned.

### Platform

- [Cursor Rules for a Project](prompts/platform/cursor-rules.md) — Concise `.cursorrules` for a stack.
- [Structured Prompt with XML Tags](prompts/platform/claude-xml-tags.md) — Tag-separated Claude prompt.

## Patterns

- [Role + Constraint + Format](patterns/role-constraint-format.md) — The foundation of most reliable prompts.

## Contributing

Please follow the format in [templates/prompt-template.md](templates/prompt-template.md). Prompts should be tested and include a "Why It Works" section. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

[MIT](LICENSE)