# Unstructured Text to JSON Extractor

**Platform:** Claude / ChatGPT
**Category:** Data
**Use Case:** Convert messy text (emails, notes) into clean, structured JSON.

## The Prompt
> Extract the key information from the text below and output it as a valid JSON object.
>
> The JSON should have the following schema:
> ```json
> {
>   "name": "string",
>   "email": "string",
>   "company": "string",
>   "request": "string",
>   "urgency": "high | medium | low"
> }
> ```
>
> If a field is not present in the text, use null.
> Do not include any text outside of the JSON object.
>
> Text:
> {{MESSY_TEXT}}

## Why It Works
It provides a concrete schema, handles missing fields with a default, and explicitly forbids conversational filler. This is critical for reliable data extraction.
