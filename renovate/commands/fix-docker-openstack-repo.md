---
description: Fix all failing Renovate PRs in a Docker OpenStack image repository.
allowed-tools: Bash(gh pr checkout:*), Bash(gh pr list:*), Bash(gh run list:*), Bash(gh pr view:*), Bash(gh run view:*), Bash(gh run watch:*), Bash(gh pr merge:*), Bash(git checkout:*), Bash(curl:*), Skill(git:commit-message), Skill(renovate:fix-docker-openstack-patch)
---

## Workflow

1. `gh pr list` to find all open Renovate PRs with failing checks
2. For each failing PR, invoke the `renovate:fix-docker-openstack-patch` skill
3. Return to the main branch when done
