# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Repository Purpose

PM Skills for kinaia.app — 65 product management skills across 8 domain plugins. Each skill is a standalone `SKILL.md` that encodes a proven PM framework as an AI-readable prompt. No code, no build system, no tests.

Based on [phuryn/pm-skills](https://github.com/phuryn/pm-skills) by Paweł Huryn.

## Structure

```
pm-<domain>/skills/<skill-name>/SKILL.md
```

8 plugins: `pm-product-discovery` (13), `pm-product-strategy` (12), `pm-execution` (15), `pm-market-research` (7), `pm-data-analytics` (3), `pm-go-to-market` (6), `pm-marketing-growth` (5), `pm-toolkit` (4).

## SKILL.md Format

Every skill follows this structure:

```yaml
---
name: kebab-case-id
description: "What the skill does. Use when..."
---

# Title

## Purpose / Context / Instructions / Output / Notes
```

Key conventions:
- `$ARGUMENTS` placeholder for user input
- Written as persona instructions ("You are an experienced product manager...")
- `description` in frontmatter serves as the auto-load trigger and is the canonical description used in README.md

## Editing Skills

- Keep frontmatter `description` and README.md skill table in sync — they should contain the same text
- Skills are standalone — no cross-file imports or dependencies between skills
- Maintain the persona/instruction tone, not documentation tone
