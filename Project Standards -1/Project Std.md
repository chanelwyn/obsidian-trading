---
title: Project Standards
type: standard
status: active
version: 1
phase: Phase-1
tags:
  - standards
  - project
---

# Project Standards

## Purpose
This document defines the documentation standards for the TradingOS Obsidian Vault. Every future document must comply with these standards.
## Source of Truth
If documents conflict, follow this order:
1. Master Trading System Rulebook
2. Combined Setup File
3. Trading Coach Specification
4. Trade Scoring Rubric
5. Trade Review Intake Template
6. Project Standards
7. Templates
8. Journals and Notes

Higher-priority documents always override lower-priority documents.
## Documentation Principles
- One document = one responsibility.
- Permanent knowledge is written once.
- Link instead of duplicate.
- Use objective, technical language.
- Make documents easy to scan.
- Unknown information remains unknown.
- Rules are deterministic whenever possible.
## Document Types

### Permanent
Defines the TradingOS.
- Standards
- Rulebooks
- Setup Cards
- Playbooks
- SOPs
- Reference Guides
### Operational
Applies the system.
- Daily Prep
- Trade Plans
- Watchlists
- Checklists
### Review
Evaluates execution.
- Trade Reviews
- Replay Reviews
- Performance Reports
### Archive
Historical material that no longer affects the current system.

## Vault Philosophy
The vault is documentation, not a notebook.
- Each file represents one concept.
- Folders organise categories.
- Wiki links are the primary navigation.
- Avoid duplicated information.
- Prefer one document per workflow or concept—not one document per heading.
## Standard Document Structure
Unless a dedicated template exists, permanent documents should follow:
1. YAML
2. Purpose
3. Scope
4. Main Content
5. Rules
6. References
7. Related Documents

## Heading Hierarchy
```text
# Document Title
## Major Section
### Subsection
#### Detail
```
Do not skip heading levels.

## Naming Rules
- Use descriptive names.
- Avoid abbreviations unless universally recognised.
- One concept per file.
- Rename files when the scope changes.
## Writing Rules
- Be concise.
- Prefer lists over paragraphs.
- Avoid repetition.
- Avoid motivational language.
- Avoid unnecessary explanations.
- Define rules, not opinions.
- Keep formatting consistent across the vault.
## Linking Rules
- Every permanent document should link to related documents.
- Do not duplicate rules from another file.
- Link to the authoritative document instead.
- Broken links should not exist.
## Status Values

| Status     | Meaning           |
| ---------- | ----------------- |
| Draft      | In development    |
| Active     | Official standard |
| Review     | Pending revision  |
| Deprecated | Superseded        |
| Archived   | Historical only   |

Only **Active** documents define the current TradingOS.

## Change Policy
Permanent documents are updated only when:
- a trading rule changes
- documentation is restructured
- contradictions are resolved
- clarification improves precision

Trading results alone do not change permanent documentation.

## Future Compatibility
Every future phase of the TradingOS must follow these standards. Any new documentation standard should extend this system rather than replace it.
## Related Documents
- [[Formatting Guide]]
- [[YAML Standard]]
- [[Naming Convention]]
- [[Folder Convention]]
- [[Tag Convention]]
- [[Internal Linking Rules]]
- [[Callout Style Guide]]
- [[Writing Style Guide]]
- [[Templates overview]]