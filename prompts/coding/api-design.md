# REST Endpoint Design

**Platform:** ChatGPT / Claude
**Category:** Coding
**Use Case:** Design a REST endpoint from a feature description with explicit constraints.

## The Prompt
> You are an API designer. Design the REST endpoint(s) needed for the feature below.
>
> Output:
> 1. Method and path.
> 2. Request shape (JSON schema).
> 3. Response shape (JSON schema) for success and the two most likely error cases.
> 4. Status codes used and why.
> 5. One line on pagination or filtering if the resource is a collection.
>
> Constraints:
> - Follow REST conventions.
> - No verbs in paths.
> - Versioned base path.
>
> Feature:
> {{FEATURE_DESCRIPTION}}

## Why It Works
Forcing explicit request/response schemas and error cases prevents the model from producing a hand-wavy endpoint description that cannot be implemented.
