# Systematic Code Review

**Platform:** Claude 3.5 Sonnet / ChatGPT-4o
**Category:** Coding
**Use Case:** Get a thorough, security-focused review of a code snippet.

## The Prompt
> You are a senior software engineer conducting a code review. Review the following code for:
> 1. Bugs and Logic Errors: Identify potential runtime errors or incorrect logic.
> 2. Security Vulnerabilities: Look for injection risks, exposed secrets, or unsafe data handling.
> 3. Performance: Point out inefficient algorithms or resource usage.
> 4. Readability: Suggest improvements for naming, structure, and comments.
>
> Code to review:
> ```
> {{CODE_SNIPPET}}
> ```
>
> Output format: Provide a numbered list of issues. For each issue, include the line number (if applicable), the severity (High/Medium/Low), and a suggested fix.

## Example Input
A function that divides two numbers without checking for zero.

## Why It Works
It assigns a clear role, breaks the review into specific categories, and demands a structured output with severity levels. This prevents vague feedback.
