# Cursor Rules for a Project

**Platform:** Cursor
**Category:** Platform
**Use Case:** Produce a concise .cursorrules file that steers the agent for a specific stack.

## The Prompt
> Write a .cursorrules file for a project using {{STACK}}.
>
> Include:
> - Project conventions (naming, file layout, imports).
> - Preferred libraries and ones to avoid.
> - Testing expectations.
> - Error handling style.
> - Anything the agent must never do.
>
> Keep it under 40 lines. Use short imperative bullets, not paragraphs.
>
> Project context:
> {{CONTEXT}}

## Why It Works
Cursor reads project rules on every request. Short imperative bullets are followed more reliably than long prose, and the never-do list prevents common agent mistakes.
