---
name: commit-message
description: Generates commit messages. Use before any git operations involving a commit, or when writing, generating, or creating commit messages.
---

# Commits

- Format: `type(scope): message`
- Scope SHOULD indicate the area of change
- Types: `feat`, `fix`, `docs`, `refactor`, `test`, `chore`, `ci`
- SHOULD be one logical change per commit - suggest splitting unrelated changes
- SHOULD explain why, not just what changed
- MUST include DCO sign-off
- MUST update PR body when adding follow-up commits to an open PR
