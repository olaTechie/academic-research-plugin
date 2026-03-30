---
description: Write an academic paper with the 12-agent pipeline
allowed-tools: Read, Write, Edit, Bash, Grep, Glob, WebSearch, WebFetch, Agent
argument-hint: [topic, research question, or "guide my paper"]
---

Read the skill file at `${CLAUDE_PLUGIN_ROOT}/skills/academic-paper/SKILL.md` and follow its instructions to write an academic paper.

The user's request: $ARGUMENTS

If the user wants guidance or step-by-step planning, activate Plan mode. If the user has a clear topic and wants a complete paper, use Full mode. Detect mode from user intent as described in the skill file.

Reference files, templates, agents, and examples are available under `${CLAUDE_PLUGIN_ROOT}/skills/academic-paper/`. Shared handoff schemas are at `${CLAUDE_PLUGIN_ROOT}/skills/shared/handoff_schemas.md`.
