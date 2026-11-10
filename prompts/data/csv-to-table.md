# CSV to Clean Markdown Table

**Platform:** Any modern LLM
**Category:** Data
**Use Case:** Convert raw CSV into a readable markdown table with cleanup.

## The Prompt
> Convert the CSV below into a markdown table.
>
> Rules:
> - Trim whitespace from every cell.
> - Normalize dates to YYYY-MM-DD.
> - Replace empty cells with "n/a".
> - Do not change column order.
>
> CSV:
> {{CSV_DATA}}

## Why It Works
Explicit normalization rules produce consistent output across runs, which matters when the table feeds downstream docs.
