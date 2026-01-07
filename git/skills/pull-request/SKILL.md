---
name: pull-request
description: Creates and opens pull requests from unmerged changes. Use when user asks to open a PR, create a pull request, make a PR, submit a PR, or handle unmerged/staged/unstaged changes that need a PR.
---

# Pull Requests

- MUST use the commit-message skill to craft git commit messages
- Title MUST follow conventional commits format: `type(scope): message`
- Title is used for squash merge commit
- SHOULD include `Closes` or `Related` referencing GitHub or Jira issue if possible
- SHOULD explain why, not just what changed
- SHOULD add reviewers based on git history of changed files
- SHOULD NOT include test plan
