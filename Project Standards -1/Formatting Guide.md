---
title: Formatting Guides
type: standard
status: active
version: 1
phase: Phase-1
tags:
  - standards
  - markdown
---
# Markdown Style Guide

## Purpose
Defines the Markdown formatting standard for every document in the TradingOS.

## General Rules
- Use standard Markdown only.
- Optimise for Obsidian readability.
- Keep formatting clean and consistent.
- Prefer simple structure over visual decoration.
- Keep documents compact; avoid unnecessary whitespace.
- Limit Heading depth (≤4)
- Max 1-2 callouts
- prefer checklist
- avoid decorative sections
- compact spacing

## Headings
Rules:
- One `#` heading per document.
- Do not skip heading levels.
- Prefer a maximum depth of `####`.

Example:

```markdown
# Title
## Section
### Subsection
#### Detail
```

## Paragraphs
- Keep paragraphs short.
- Prefer lists over large text blocks.
- Insert blank lines only when readability improves.
- Avoid walls of text.

## Lists

### Unordered

```markdown
- Item
- Item
  - Sub-item
```

### Ordered

```markdown
1. First
2. Second
3. Third
```

Rules:
- Keep nesting shallow.
- Use numbered lists only when order matters.

## Text Formatting

| Format | Purpose |
|---------|---------|
| **Bold** | Rules, important terms |
| *Italic* | Definitions or emphasis |
| `Code` | Files, fields, commands, tags |

Avoid excessive formatting.

## Code Blocks
Always specify the language.

```yaml
status: active
version: 1.0
```

Supported languages:
- yaml
- markdown
- text
- json
- bash
- powershell

## Inline Code
Use backticks for:
- file names
- YAML fields
- tags
- folder names
- commands

Example:

```markdown
`Project Standards.md`
```

## Tables
Use tables only for structured information.

```markdown
| Item | Value |
|------|-------|
| A | B |
```

Do not place long paragraphs inside tables.

## Checklists
Use checklists only for actions.

```markdown
- [ ] Task
- [x] Complete
```

Do not use checklists for reference material.

## Callouts
Use Obsidian callouts only.

```markdown
> [!note]
> Content
```

Refer to [[Callout Style Guide]] for approved callout types.

## Images
Use relative image links.

```markdown
![[chart.png]]
```

If an image is pending, use a placeholder.

```markdown
> [!todo]
> Insert chart.
```

## Internal Links

Standard link:

```markdown
[[Capitulation Long]]
```

Heading link:

```markdown
[[Capitulation Long#Entry Trigger]]
```

Alias:

```markdown
[[Capitulation Long|Capi Long]]
```

External link:

```markdown
[TradingView](https://www.tradingview.com)
```

## Horizontal Rules
Use only between major sections.

```markdown
---
```

Avoid unnecessary separators.

## Spacing

### General Rules
- Keep documents vertically compact.
- Use one blank line only when separating logical sections.
- Never use consecutive blank lines.
- Do not insert blank lines after headings unless readability requires it.

### Labels

Place examples immediately after their label.

Correct:

```markdown
Example:
```text
RVOL >5x
```

Not:
```text
Relative Volume > five times.
```
```

Incorrect:

```markdown
Example:

```text
RVOL >5x
```

Not:

```text
Relative Volume > five times.
```
```

### Lists

Do not insert blank lines between consecutive list items.

Correct:

```markdown
- Rule 1
- Rule 2
- Rule 3
```

### Tables

Leave one blank line before and after a table when it improves readability.

### Code Blocks

Place code blocks immediately below their label.

Correct:

```markdown
Example:
```yaml
status: active
```
```

Incorrect:

```markdown
Example:

```yaml
status: active
```


## Formatting Rules
- Use consistent indentation.
- Remove trailing spaces.
- Keep blank lines to a minimum.
- Avoid HTML.
- Avoid emojis.
- Avoid coloured text.
- Avoid excessive nesting.
- Keep every document easy to scan.

## Related Documents
- [[Project Standards]]
- [[YAML Standard]]
- [[Internal Linking Rules]]
- [[Callout Style Guide]]
- [[Writing Style Guide]]