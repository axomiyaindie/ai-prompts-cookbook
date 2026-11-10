# Debug an Error Message

**Platform:** Claude / ChatGPT / Cursor
**Category:** Coding
**Use Case:** Diagnose a runtime error from a stack trace and code context.

## The Prompt
> You are a debugging assistant. Given the error and code below, identify the most likely root cause and propose the minimal fix.
>
> Output:
> 1. Root cause (one paragraph).
> 2. Minimal fix (code diff or snippet).
> 3. How to verify the fix.
>
> Error:
> ```
> {{ERROR_MESSAGE}}
> ```
>
> Relevant code:
> ```
> {{CODE_CONTEXT}}
> ```

## Why It Works
It separates diagnosis from fix from verification, which mirrors how experienced engineers debug and prevents the model from jumping to a guess.
