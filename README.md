# Academic Research Plugin

A comprehensive academic research and paper writing toolkit for Claude, bundling four interconnected skills into a single plugin.

## Overview

This plugin provides an end-to-end academic research workflow — from initial research exploration through paper writing, peer review, and final publication-ready formatting. It includes 4 skills and 4 slash commands.

## Components

### Skills

| Skill | Description |
|-------|-------------|
| **deep-research** | 13-agent pipeline for rigorous academic research. Supports 7 modes: full research, quick brief, paper review, lit-review, fact-check, Socratic guided dialogue, and PRISMA systematic review with meta-analysis. |
| **academic-paper** | 12-agent pipeline for academic paper writing. Supports IMRaD, literature review, theoretical, case study, policy brief, and conference paper structures. APA 7.0, Chicago, MLA, IEEE, Vancouver citations. Bilingual abstracts (zh-TW + EN). Multi-format output (LaTeX, DOCX, PDF, Markdown). |
| **academic-paper-reviewer** | 7-agent multi-perspective peer review simulator. 5 independent reviewers (EIC + 3 peers + Devil's Advocate) with field-specific expertise. Supports full review, re-review, quick assessment, methodology focus, and Socratic guided modes. |
| **academic-pipeline** | Orchestrator for the full 10-stage research-to-publication workflow. Coordinates deep-research, academic-paper, and academic-paper-reviewer with mandatory integrity verification, two-stage peer review, and quality gates. |

### Commands

| Command | Description |
|---------|-------------|
| `/research [topic]` | Start a deep research investigation |
| `/write-paper [topic]` | Write an academic paper |
| `/review-paper [file]` | Simulate multi-perspective peer review |
| `/pipeline [topic]` | Run the full research-to-publication pipeline |

## Usage

### Starting from Scratch
Use `/pipeline` to run the full workflow, or `/research` followed by `/write-paper` for more control over each phase.

### Writing a Paper
Use `/write-paper` with your topic. Say "guide my paper" to activate Socratic plan mode for step-by-step guidance.

### Reviewing a Manuscript
Use `/review-paper` and provide your manuscript. The system will configure 5 field-specific reviewers automatically.

### Deep Research Only
Use `/research` for standalone research without paper writing. Supports systematic reviews and meta-analysis.

## Setup

No external configuration or environment variables required. The plugin works out of the box with Claude's built-in tools.

## Credits

Based on the [academic-research-skills](https://github.com/olaTechie/academic-research-skills) repository.
