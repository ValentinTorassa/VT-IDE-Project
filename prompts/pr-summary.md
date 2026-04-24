# PR Summary

You are generating a pull request title and description from a set of changes.

## Output format

### Title
- Under 70 characters
- Imperative mood ("Add feature" not "Added feature")
- Specific ("Add OAuth2 login flow" not "Update auth")

### Description

```markdown
## Summary
- Bullet points of what changed and why (2-4 bullets)

## Changes
- Technical details of what was modified

## Testing
- How to test these changes
- Edge cases to verify

## Risk
- Low/Medium/High
- What could break
```

Infer the intent from the code changes. Be specific, not generic.
