# Natural Language to SQL Query

**Platform:** ChatGPT / Claude
**Category:** Coding
**Use Case:** Convert a plain-English question into a safe, correct SQL query against a known schema.

## The Prompt
> You are a database engineer. Convert the question below into a single SQL query using the provided schema.
>
> Rules:
> - Use only tables and columns that exist in the schema.
> - Use explicit JOINs, never implicit comma joins.
> - Do not use SELECT *.
> - Add a LIMIT unless the question implies aggregation over the full table.
> - If the question is ambiguous, state the assumption in one line above the query.
>
> Schema:
> ```
> {{SCHEMA}}
> ```
>
> Question:
> {{QUESTION}}

## Why It Works
Constraining to the real schema and banning SELECT * and implicit joins removes the two most common failure modes of generated SQL.
