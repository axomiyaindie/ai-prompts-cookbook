# Refactor Function for Readability

**Platform:** Claude / ChatGPT / Cursor
**Category:** Coding
**Use Case:** Improve a working function without changing its behavior.

## The Prompt
> You are a senior engineer. Refactor the following function for readability and maintainability without changing its behavior. Keep the public signature identical.
>
> Rules:
> - Do not add new dependencies.
> - Preserve error handling and edge cases.
> - Add brief comments only where intent is non-obvious.
>
> Output:
> 1. The refactored code.
> 2. A short list of what changed and why.
>
> Function:
> ```
> {{FUNCTION_CODE}}
> ```

## Why It Works
It constrains the model to behavior-preserving changes and forces it to justify each edit, which prevents gratuitous rewrites.
