# Claude Code Plugins

A collection of plugins for Claude Code.

## Concepts

- **Agent Skills**: Automatically invoked by Claude Code when relevant to your task. You can also explicitly invoke them using the Skill tool (e.g., `git:commit-message`).
- **Commands**: User-invoked workflows triggered by typing the command name (e.g., `/git:commit-push-pr`).

## Plugins

| Plugin | Description |
|--------|-------------|
| [`git`](git/README.md) | Streamlines Git workflows by generating standardized commit messages and pull requests |
