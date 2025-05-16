# AI Security, Ethics & Best Practices

As we start using AI tools more often in our daily work, it’s important to follow a few best practices to make sure we’re using them responsibly and securely.

## Security Precautions
- **Keep credentials private**: Never include API keys, tokens, login credentials, or personal information in prompts.
- **Double-check before use**: Review any AI-generated code or configuration carefully, especially before deploying it.
- **Watch out for errors**: AI can make things up or get things wrong. Sanity-check the logic, syntax, and dependencies.
- **Avoid risky commands**: Don’t rely on AI for dangerous shell or database commands (like `rm -rf` or `DROP TABLE`), even in test environments.

## Code & Repository Hygiene
- **Make it clear if AI helped**: If AI generated part of your code, leave a comment and note in the PR so others know.
- **Don’t push without reviewing**: Always review AI output before committing it — treat it like code from a junior teammate.
- **Use `.gitignore` properly**: Make sure you’re not accidentally committing debug dumps or generated secrets.

## Prompting Guidelines
- **Don’t dump full files**: Avoid pasting long codebases or sensitive info into prompts.
- **Share good prompts**: If you find prompts that work well, consider saving and sharing them with the team.

## Ethics & Responsible Use
- **Be mindful of bias**: AI can reflect harmful or unfair biases — especially in user-facing or decision-making features.
- **Don’t mislead**: Don’t use AI to generate content that’s intentionally misleading or deceptive.
- **Respect licenses**: If the AI generates something that looks like third-party code, double-check its source and license before using it.

## Quick Checklist

Before using AI-generated content, make sure:
- No secrets or credentials were included in your prompt.
- You’ve reviewed the output yourself.
- The code doesn’t introduce security issues.
- It’s clear what parts (if any) came from AI.
- The output doesn’t violate any licenses or terms of use.