# Generate Unit Tests

**Platform:** Claude / ChatGPT / Cursor
**Category:** Coding
**Use Case:** Produce a focused test suite for an existing function.

## The Prompt
> You are a test engineer. Write unit tests for the following function using {{FRAMEWORK}} (e.g., pytest, Jest, JUnit).
>
> Requirements:
> - Cover the happy path, boundary values, and at least two failure cases.
> - Mock external dependencies where needed.
> - One assertion per test.
> - Name tests descriptively.
>
> Function:
> ```
> {{FUNCTION_CODE}}
> ```

## Why It Works
Specifying the framework, the coverage categories, and the assertion style gives a predictable, reviewable output instead of a vague test blob.
