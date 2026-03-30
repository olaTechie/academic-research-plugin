---
description: Simulate multi-perspective peer review of a manuscript
allowed-tools: Read, Write, Edit, Bash, Grep, Glob, Agent
argument-hint: [path to paper or "paste paper"]
---

Read the skill file at `${CLAUDE_PLUGIN_ROOT}/skills/academic-paper-reviewer/SKILL.md` and follow its instructions to conduct a multi-perspective peer review.

The user's request: $ARGUMENTS

Select the appropriate mode (full, re-review, quick, methodology-focus, or guided) based on user intent as described in the skill file.

Reference files, templates, agents, and examples are available under `${CLAUDE_PLUGIN_ROOT}/skills/academic-paper-reviewer/`.
