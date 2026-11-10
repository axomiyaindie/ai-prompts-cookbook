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
- [Patterns](#patterns)
- [Contributing](#contributing)
- [License](#license)

## Structure
.
├── prompts/ Ready-to-use prompts by category
│ ├── coding/
│ ├── writing/
│ ├── data/
│ └── image/
├── patterns/ Reusable techniques behind reliable prompts
└── templates/ The blank recipe template used for contributions

text

## How to Use

1. Browse to the relevant category below.
2. Open the prompt file.
3. Copy the prompt.
4. Replace the `{{PLACEHOLDERS}}` with your own content.
5. Paste into your AI tool (ChatGPT, Claude, Cursor, Midjourney, etc.).

## Prompts by Category

### Coding
- [Systematic Code Review](prompts/coding/code-review.md) — Thorough, security-focused review of a code snippet.

### Writing
- [Executive Article Summarizer](prompts/writing/summarize-article.md) — Turn a long article into a concise, actionable summary.

### Data
- [Unstructured Text to JSON Extractor](prompts/data/extract-json.md) — Convert messy text into clean, structured JSON.

### Image Generation
- [Portrait with Cinematic Lighting](prompts/image/portrait-lighting.md) — Generate a portrait with a specific photographic style.

## Patterns

- [Role + Constraint + Format](patterns/role-constraint-format.md) — The foundation of most reliable prompts.

## Contributing

Please follow the format in [templates/prompt-template.md](templates/prompt-template.md). Prompts should be tested and include a "Why It Works" section. See [CONTRIBUTING.md](CONTRIBUTING.md) for details.

## License

[MIT](LICENSE)
