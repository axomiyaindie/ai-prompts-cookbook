# Pattern: Role + Constraint + Format

**Why it works:** LLMs are stateless. They need to be reminded of their role and the rules of the task every time. This pattern is the foundation of most reliable prompts.

## The Structure
1. Role: Tell the model who it is. This sets tone and expertise level.
2. Constraint: Tell the model what it must not do, or what boundaries to respect.
3. Format: Tell the model exactly how to present the answer.

## Example
- Role: "You are a strict Python linter."
- Constraint: "Do not suggest code that uses external libraries."
- Format: "Output a markdown table with columns: Line, Issue, Fix."

This is more reliable than a vague instruction like "Check my Python code" because it eliminates ambiguity.
