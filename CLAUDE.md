# Claude Code Plugins Development

## Plugin Description Guidelines

**README.md** (for humans reading the repo):
- Start with "A Claude Code plugin that..."
- Full sentence describing the plugin's purpose

**plugin.json** (for programmatic use):
- Concise, action-oriented description
- Start with a verb (e.g., "Manages...", "Streamlines...", "Automates...")
- Do not include "A Claude Code plugin" - it's implied by context

## Plugin Structure

```
plugin-name/
├── .claude-plugin/
│   └── plugin.json       # Plugin metadata (name, version, description)
├── commands/
│   └── command-name.md   # User-invoked commands (/plugin:command)
├── skills/
│   └── skill-name/
│       └── SKILL.md      # Auto-invoked agent skills
└── README.md             # Plugin documentation
```

## Conventions

- Command files use kebab-case (e.g., `fix-renovate-pr.md`)
- Skill directories use kebab-case (e.g., `commit-message/`)
- Commands start with `# /plugin:command-name` header
- Skills use YAML frontmatter for metadata
