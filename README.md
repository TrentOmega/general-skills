# general-skills

Project-agnostic AI agent skills, templates, and helper files for reuse across repositories.

## Purpose

This repository is a shared source of truth for reusable agent workflows that should not live inside a single project.

## Repository Layout

- `.codex/skills/`: reusable skills and their supporting files.
- `README.md`: overview and skill index.
- `AGENTS.md`: repo-specific maintenance guidance.

## Available Skills

### `thread-context-capture`

Distill AI agent threads into durable project and cross-project memory notes.

Provides:
- note templates for project and portable memory
- a helper script to scaffold new memory notes
- explicit guidance for when to update an existing note versus create a new one

Path:
- `.codex/skills/thread-context-capture/`

## Usage

Copy the relevant skill directory into a target repository `.codex/skills/` tree, or use this repository directly as a shared reference.

## Contribution Rule

Only add skills and agent files that are genuinely project-agnostic.
