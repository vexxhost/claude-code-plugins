# /commit-push-pr

Create a commit, push, and open a pull request with the current changes.

## Workflow

1. Invoke the `git:commit-message` skill using the Skill tool to craft the commit message
2. Stage, commit, and push the changes to a new branch
3. Invoke the `git:pull-request` skill using the Skill tool to create the PR
