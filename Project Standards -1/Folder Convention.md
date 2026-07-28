---
title: Folder Convention
type: standard
status: active
version: 1.0
phase: Phase-1
tags: [standards, folders]
---

# Folder Convention

## Purpose
Defines the folder structure for the TradingOS. Folders organise documents by category only; navigation should primarily rely on wikilinks.

## General Rules
- One purpose per folder.
- Keep folder depth as shallow as possible.
- Store each document in the most appropriate category.
- Do not duplicate documents across folders.
- Move documents instead of copying them.
- Use folders for organisation, not relationships.

## Folder Naming
Rules:
- Use Title Case.
- Use descriptive names.
- Avoid abbreviations unless universally recognised.
- Do not use numbering unless required for project phases.

Examples:

```text
Standards
Setups
Playbooks
Journals
Templates
Archive
```

## Recommended Vault Structure

```text
TradingOS/
├── Standards/
├── Rulebook/
├── Setups/
├── Playbooks/
├── Risk Management/
├── Psychology/
├── Execution/
├── Reviews/
├── Templates/
├── Dashboards/
├── Assets/
│   ├── Images/
│   ├── Charts/
│   └── Attachments/
├── Journal/
└── Archive/
```

## Standards
Contains permanent documentation governing the vault.

Examples:
- Project Standards
- Markdown Style Guide
- YAML Standard

## Rulebook
Contains the master trading rules and core references.

Examples:
- Master Trading System Rulebook
- Combined Setup File

## Setups
Contains one document per trading setup.

Examples:
- Capitulation Long
- Bouncy Ball Short
- Opening Drive

## Playbooks
Contains workflow and process documentation.

Examples:
- Daily Preparation
- Market Open Routine
- Replay Workflow

## Risk Management
Contains position sizing and risk rules.

Examples:
- Position Sizing
- Daily Loss Limits
- Risk Framework

## Psychology
Contains behavioural and performance documentation.

Examples:
- FOMO
- Revenge Trading
- Discipline

## Execution
Contains execution-specific documentation.

Examples:
- Entry Rules
- Exit Rules
- Tape Reading

## Reviews
Contains completed trade reviews and performance reports.

Examples:
- Trade Reviews
- Weekly Reviews
- Monthly Reports

## Templates
Contains reusable document templates.

Examples:
- Trade Review Template
- Daily Prep Template
- Setup Card Template

## Dashboards
Contains navigation pages and indexes.

Examples:
- Trading Dashboard
- Performance Dashboard

## Assets
Stores non-Markdown files.

```text
Assets/
├── Images/
├── Charts/
├── PDFs/
└── Attachments/
```

Rules:
- Do not mix assets with Markdown documents.
- Use relative links when embedding assets.

## Journal
Contains operational notes.

Examples:

```text
2026-07-28 Daily Journal
2026-08-03 Replay Notes
```

## Archive
Stores deprecated or historical material.

Rules:
- Do not delete permanent documentation.
- Move obsolete files into Archive.
- Archived files should not define active rules.

## Folder Rules
- One concept belongs in one folder.
- Avoid nested folders unless they improve organisation.
- Do not organise by file type.
- Keep folder names stable.
- Use wikilinks instead of navigating folders.

## Navigation
Primary navigation should use:
- Wikilinks
- Dashboards
- Index pages
- Backlinks

Folder navigation should be secondary.

## Avoid
- Deep folder hierarchies.
- Duplicate folders.
- Empty folders.
- Generic folders such as `Misc` or `Temp`.
- Multiple archive locations.

## Related Documents
- [[Project Standards]]
- [[Naming Convention]]
- [[Internal Linking Rules]]
- [[Templates overview]]