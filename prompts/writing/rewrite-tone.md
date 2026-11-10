# Rewrite in a Target Tone

**Platform:** ChatGPT / Claude / Gemini
**Category:** Writing
**Use Case:** Rewrite a passage in a specific tone without losing meaning.

## The Prompt
> Rewrite the passage below in a {{TONE}} tone (e.g., formal, casual, persuasive, neutral).
>
> Rules:
> - Preserve all facts and key points.
> - Keep the length within 10 percent of the original.
> - Do not add new claims.
>
> Passage:
> {{PASSAGE}}

## Why It Works
The length and no-new-claims constraints stop the model from drifting into invention, which is the usual failure mode of tone rewrites.
