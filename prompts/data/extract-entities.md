# Named Entity Extraction to JSON

**Platform:** Claude / ChatGPT
**Category:** Data
**Use Case:** Pull people, organizations, locations, and dates from free text.

## The Prompt
> Extract named entities from the text below.
>
> Output a JSON object with keys: people, organizations, locations, dates.
> Each key maps to an array of strings.
> Use the exact surface form from the text.
> If a category has no matches, use an empty array.
> Do not include any text outside the JSON.
>
> Text:
> {{TEXT}}

## Why It Works
Fixed keys and empty arrays make the output parseable without branching, and requiring the exact surface form avoids normalization errors.
