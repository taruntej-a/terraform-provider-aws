<!-- Copyright IBM Corp. 2014, 2026 -->
<!-- SPDX-License-Identifier: MPL-2.0 -->

# GitHub Copilot Instructions

Full agent guidance is in [`AGENTS.md`](../AGENTS.md) at the repository root. Read it when total context is required.

## Skills

When a task matches a skill's trigger phrases, read the `SKILL.md` file for that skill before proceeding.

| Skill | Trigger phrases | Path |
|---|---|---|
| `breaking-changes` | Review PR for breaking changes, check breaking changes | `.agents/skills/breaking-changes/SKILL.md` |
| `changelog` | Add changelog entry, create changelog, write changelog | `.agents/skills/changelog/SKILL.md` |
| `fixdocs` | Fix documentation, fix docs, run swissshepherd | `.agents/skills/fixdocs/SKILL.md` |
| `reviewdocs` | Review documentation, review docs PR, check docs | `.agents/skills/reviewdocs/SKILL.md` |
