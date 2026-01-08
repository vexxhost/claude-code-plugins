---
description: Fix a failing Renovate PR in a Docker OpenStack image repository.
argument-hint: [pr]
allowed-tools: Bash(gh pr checkout:*), Bash(gh run list:*), Bash(gh pr view:*), Bash(gh run view:*), Bash(gh run watch:*), Bash(gh pr merge:*), Bash(git checkout:*), Bash(curl:*), Skill(git:commit-message), Skill(renovate:fix-docker-openstack-patch)
---

Invoke the `renovate:fix-docker-openstack-patch` skill with the PR.
