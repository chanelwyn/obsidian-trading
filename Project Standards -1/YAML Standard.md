---
title: YAML Standard
type: standard
status: active
version: 1.0
phase: Phase-1
tags: [standards, yaml]
---
# YAML Standard
## Purpose
Defines the frontmatter (YAML) standard for every document in the TradingOS. Every file should begin with a YAML block.
## Rules
- YAML must be the first element in the file.
- Keep field names consistent across the vault.
- Omit fields that are not applicable.
- Do not invent new fields unless they become project standards.
## Standard Template
```yaml
---
title:
type:
status: active
version: 1.0
created:
updated:
tags: []
---
```
## Core Fields
| Field | Required | Description |
|--------|----------|-------------|
| `title` | Yes | Document title |
| `type` | Yes | Document category |
| `status` | Yes | Document status |
| `version` | Yes | Document version |
| `created` | No | Creation date |
| `updated` | No | Last update |
| `tags` | Yes | Vault tags |
## Standard Types
```yaml
type: standard
```
Supported values:
- standard
- rulebook
- setup
- playbook
- guide
- checklist
- template
- review
- journal
- reference
- glossary
- dashboard
- archive
## Status Values
```yaml
status: active
```
Supported values:
- draft
- active
- review
- deprecated
- archived
## Version Format
```yaml
version: 1.0
```
Rules:
- Major changes increment the whole number.
- Minor documentation updates increment the decimal.
- Do not version temporary documents.
## Date Format
```yaml
created: 2026-07-28
updated: 2026-07-28
```
Use ISO-8601 (`YYYY-MM-DD`) throughout the vault.
## Tags
```yaml
tags:
  - standards
  - markdown
```
Rules:
- Use lowercase.
- Use singular nouns where practical.
- Avoid duplicate tags.
- Follow [[Tag Convention]].
## Optional Fields
```yaml
aliases:
parent:
source:
phase:
reviewed:
```
Use only when relevant.
### aliases
```yaml
aliases:
  - Capi
  - Capitulation
```
Alternative names for search and linking.
### parent
```yaml
parent: Setups
```
Groups related documents.
### source
```yaml
source:
  - Master Trading System Rulebook
```
References the authoritative source.
### phase
```yaml
phase: Phase-3
```
Identifies the TradingOS build phase.
### reviewed
```yaml
reviewed: 2026-08-01
```
Records the latest document review.
## Permanent Document Example
```yaml
---
title: Capitulation Long
type: setup
status: active
version: 1.2
created: 2026-07-28
updated: 2026-08-03
tags:
  - setup
  - long
  - capitulation
source:
  - Master Trading System Rulebook
---
```
## Journal Example
```yaml
---
title: 2026-08-05 Trade Review - NVDA
type: review
status: active
created: 2026-08-05
tags:
  - review
  - nvda
---
```
## Rules
- One YAML block per file.
- Do not place content above YAML.
- Keep field order consistent.
- Remove empty fields.
- Keep values concise.
- Use lists instead of comma-separated values.
## Related Documents
- [[Project Standards]]
- [[Markdown Style Guide]]
- [[Naming Convention]]
- [[Tag Convention]]