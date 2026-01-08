# Claude Code Plugins

A collection of plugins for Claude Code.

## Concepts

- **Agent Skills**: Automatically invoked by Claude Code when relevant to your task. You can also explicitly invoke them using the Skill tool (e.g., `git:commit-message`).
- **Commands**: User-invoked workflows triggered by typing the command name (e.g., `/git:commit-push-pr`).

## Getting Started

### Add the Marketplace

A marketplace is a collection of plugins hosted in a GitHub repository. Adding a marketplace makes its plugins available for installation in Claude Code.

To add this marketplace, run the following command in Claude Code:

```
/plugin marketplace add vexxhost/claude-code-plugins
```

This registers the marketplace so you can browse and install plugins from it.

### Install a Plugin

Installing a plugin downloads it and enables its agent skills and commands in your Claude Code sessions. You can install plugins at different scopes:

- **User** (recommended): Available to you across all projects
- **Project**: Available to all collaborators on the repository
- **Local**: Available only to you in the current repository

To install a plugin (e.g., the `git` plugin):

```
/plugin install git@vexxhost
```

Once installed, the plugin's agent skills will automatically activate when relevant, and its commands will be available for you to invoke directly.

## Plugins

| Plugin | Description |
|--------|-------------|
| [`git`](git/README.md) | Streamlines Git workflows by generating standardized commit messages and pull requests |
| [`renovate`](renovate/README.md) | Manages Renovate workflows including fixing failing PRs and installing Renovate configurations |
