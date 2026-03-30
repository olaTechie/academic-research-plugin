---
description: Start a deep research investigation on any topic
allowed-tools: Read, Write, Edit, Bash, Grep, Glob, WebSearch, WebFetch, Agent
argument-hint: [topic or research question]
---

Read the skill file at `${CLAUDE_PLUGIN_ROOT}/skills/deep-research/SKILL.md` and follow its instructions to conduct deep research on the user's topic.

The user's research topic or question: $ARGUMENTS

If the user's intent is vague or they seem uncertain about their research direction, activate Socratic mode as described in the skill file. Otherwise, use full mode.

Reference files, templates, agents, and examples are available under `${CLAUDE_PLUGIN_ROOT}/skills/deep-research/`. Shared handoff schemas are at `${CLAUDE_PLUGIN_ROOT}/skills/shared/handoff_schemas.md`.
