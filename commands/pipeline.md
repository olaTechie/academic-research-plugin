---
description: Run the full research-to-publication pipeline
allowed-tools: Read, Write, Edit, Bash, Grep, Glob, WebSearch, WebFetch, Agent
argument-hint: [topic or "I have a paper already"]
---

Read the skill file at `${CLAUDE_PLUGIN_ROOT}/skills/academic-pipeline/SKILL.md` and follow its instructions to orchestrate the full academic pipeline.

The user's request: $ARGUMENTS

Detect the user's current stage (starting from scratch, mid-entry with existing paper, or revision mode with reviewer feedback) and begin from the appropriate pipeline stage.

All sub-skills are available under `${CLAUDE_PLUGIN_ROOT}/skills/`. Shared handoff schemas are at `${CLAUDE_PLUGIN_ROOT}/skills/shared/handoff_schemas.md`.
