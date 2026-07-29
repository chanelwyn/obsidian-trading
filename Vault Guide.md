---
title: Vault Guide
type: guide
status: active
version: 1.0
phase: Phase-0
tags:
  - guide
  - architecture
---
# Vault Guide
## Principles
- One concept per document.
- One source of truth.
- Link instead of duplicate.
- Folders organise; wikilinks navigate.
- Templates define structure.
- Permanent documents define the system.
- Operational documents apply the system.
## Structure
```text
TradingOS/
├── Home.md
├── Vault Guide.md
├── Standards/
├── Rulebook/
├── Setups/
├── Playbooks/
├── Reviews/
├── Journal/
├── Templates/
├── Assets/
└── Archive/
```
## Folder Roles
| Folder | Purpose |
|--------|---------|
| Standards | Documentation standards |
| Rulebook | Trading rules |
| Setups | Setup cards |
| Playbooks | Operating procedures |
| Reviews | Trade reviews |
| Journal | Daily notes |
| Templates | Reusable templates |
| Assets | Images & files |
| Archive | Historical material |
## Information Flow
```text
Rulebook
    ↓
Setups
    ↓
Playbooks
    ↓
Execution
    ↓
Replay
    ↓
Review
    ↓
Journal
```
## Navigation
Use:
- [[Home]]
- Wikilinks
- Backlinks
- Search
- Graph View
Avoid navigating by folders.
## Linking Rules
Always:
- Link to the authoritative document.
- Use `[[Wikilinks]]`.
- Keep one source of truth.
- Add related documents.
Never:
- Duplicate content.
- Link with folder paths.
- Leave broken links.
## Templates
Operational templates:
- [[Live Trading Template]]
- [[Constitution Template]]
- [[Setup Template]]
- [[Replay Template]]
- [[Review Template]]
- [[Journal Template]]
Templates provide structure only.
## Maintenance
- Keep folders shallow.
- Rename instead of duplicate.
- Archive instead of delete.
- Keep YAML consistent.
- Review links periodically.
## Related Documents
- [[README]]
- [[Home]]
- [[Project Standards]]
- [[Folder Convention]]
- [[Internal Linking Rules]]