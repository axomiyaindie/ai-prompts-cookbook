# Structured Prompt with XML Tags

**Platform:** Claude
**Category:** Platform
**Use Case:** Use XML tags to separate instructions, context, and input for more reliable Claude output.

## The Prompt
> <instructions>
> {{INSTRUCTIONS}}
> </instructions>
>
> <context>
> {{CONTEXT}}
> </context>
>
> <input>
> {{INPUT}}
> </input>
>
> Follow the instructions using the context, applied to the input. Output only the final result.

## Why It Works
Claude is trained to respect XML-style tag boundaries. Separating instructions, context, and input reduces bleed between them, which is the most common cause of inconsistent Claude output.
