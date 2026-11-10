# Classify Text into Fixed Labels

**Platform:** Claude / ChatGPT
**Category:** Data
**Use Case:** Assign one label from a fixed set to each text item.

## The Prompt
> Classify each item below into exactly one of these labels: {{LABEL_LIST}}.
>
> Rules:
> - If uncertain, choose the closest label and mark confidence as low.
> - Output a JSON array of objects with fields: id, label, confidence.
> - Do not include any text outside the JSON.
>
> Items:
> {{ITEMS}}

## Why It Works
A fixed label list plus a confidence field makes the output auditable and easy to route to human review where confidence is low.
