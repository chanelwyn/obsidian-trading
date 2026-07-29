---
title: Naming Convention
type: standard
status: active
version: 1.0
phase: Phase-1
tags: [standards, naming]
---
# Naming Convention
## Purpose
Defines the naming standard for every file, folder, template and asset in the TradingOS.
## General Rules
- Names should describe the content, not the category.
- Use Title Case.
- Keep names short and descriptive.
- One concept per file.
- Avoid unnecessary abbreviations.
- Rename files if their scope changes.
## File Naming
### Standard Format
```text
Descriptive Name
```
Examples:
```text
Capitulation Long
Risk Management
Trade Review Checklist
Daily Preparation
Position Sizing
```
## Do Not Use
```text
Notes
Trading Notes
Setup A
Version 2
Misc
Untitled
New Document
```
## Numbers
Use numbers only when they are part of the subject.
Correct
```text
Day 2 Continuation
2-Minute Trailing Stop
```
Incorrect
```text
Trade Rules 2
Setup Final 3
```
## Dates
Operational documents may begin with a date.
```text
2026-07-28 Daily Journal
2026-08-05 Trade Review - NVDA
```
Use ISO format:
```text
YYYY-MM-DD
```
## Setup Documents
Use the setup name.
Correct
```text
Capitulation Long
Bouncy Ball Short
Opening Drive
Multi-Day Continuation
```
Avoid internal numbering.
Incorrect
```text
Setup A
Setup B
Card 1
```
## Template Files
Append **Template**.
Examples
```text
Trade Review Template
Daily Prep Template
Setup Card Template
```
## Checklists
Append **Checklist**.
Examples
```text
Pre-Trade Checklist
Market Open Checklist
Post-Trade Checklist
```
## Dashboards
Append **Dashboard**.
Examples
```text
Trading Dashboard
Performance Dashboard
```
## Guides
Append **Guide**.
Examples
```text
Markdown Guide
Execution Guide
Replay Guide
```
## Standards
Append **Standard** or **Style Guide**.
Examples
```text
YAML Standard
Markdown Style Guide
Writing Style Guide
```
## File Extensions
Do not include extensions in links.
Correct
```markdown
[[Risk Management]]
```
Incorrect
```markdown
[[Risk Management.md]]
```
## Characters
Allowed:
- Letters
- Numbers
- Spaces
- Hyphen (`-`) when necessary
Avoid:
- Underscores (`_`)
- Multiple hyphens
- Symbols
- Emojis
- Leading or trailing spaces
## Acronyms
Use recognised trading acronyms only.
Examples
```text
SPY
QQQ
VWAP
EMA
SSR
```
Spell uncommon terms in full.
## Aliases
Use YAML aliases instead of duplicate files.
Example
```yaml
aliases:
  - Capi
  - Capitulation
```
## Consistency
Files covering similar topics should follow the same naming pattern.
Examples
```text
Capitulation Long
Bouncy Ball Short
Opening Drive
Breakout Long
```
Not
```text
Capitulation
The Bounce Setup
Opening Drive Strategy
Long Breakout Play
```
## Avoid
- Generic names
- Personal abbreviations
- Duplicate names
- Version numbers
- "Final", "New", "Old", "Copy"
- Mixed naming styles
## Related Documents
- [[Project Standards]]
- [[Folder Convention]]
- [[Internal Linking Rules]]
- [[YAML Standard]]