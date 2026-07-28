---
title: Tag Convention
type: standard
status: active
version: 1.0
phase: Phase-1
tags: [standards, tags]
---

# Tag Convention

## Purpose
Defines the tagging standard for the TradingOS. Tags improve search, filtering and dashboards. They do not replace folders or wikilinks.

## General Rules
- Use tags sparingly.
- Use lowercase only.
- Use singular nouns where practical.
- One word per tag unless a phrase is necessary.
- Avoid duplicate or synonymous tags.
- Do not use tags as categories when folders already provide the organisation.

## Standard Format

```yaml
tags:
  - setup
  - review
  - psychology
```

## Tag Categories

### Document Type

```text
standard
guide
template
setup
playbook
rulebook
review
journal
dashboard
reference
checklist
archive
```

### Trading Direction

```text
long
short
```

### Trading Discipline

```text
entry
exit
execution
risk
psychology
planning
review
```

### Market Context

```text
premarket
open
intraday
multiday
trend
range
reversal
breakout
```

### Asset

```text
stock
etf
index
```

### Priority

```text
high-priority
medium-priority
low-priority
```

Use only when meaningful.

## Permanent Document Example

```yaml
tags:
  - setup
  - long
  - breakout
```

## Review Example

```yaml
tags:
  - review
  - execution
  - psychology
```

## Standard Document Example

```yaml
tags:
  - standards
  - markdown
```

## Naming Rules
- Lowercase only.
- Separate words using hyphens.
- No spaces.
- No punctuation.
- No emojis.
- No file extensions.

Correct:

```text
risk-management
market-open
trade-review
```

Incorrect:

```text
Risk
Trade Review
review!
review_v2
```

## When to Create a Tag
Create a new tag only if it:
- Represents a recurring concept.
- Will be used across multiple documents.
- Improves filtering or dashboards.

Otherwise, use a wikilink instead.

## When to Use Wikilinks Instead
Use a wikilink when referencing:
- A specific setup.
- A document.
- A checklist.
- A rule.
- A guide.
- A playbook.

Correct:

```markdown
[[Capitulation Long]]
```

Not:

```text
#capitulation
```

## Tag Limits
Recommended:
- 2–5 tags per document.

Avoid:
- More than 8 tags.
- Tags that repeat the folder name.
- Tags used only once.
- Multiple tags with the same meaning.

## Do Not Tag
Avoid tagging:
- Dates
- File names
- Version numbers
- Personal initials
- Temporary projects
- Random keywords

## Maintenance
Review tags periodically to:
- Merge duplicates.
- Remove unused tags.
- Keep naming consistent.
- Maintain a controlled vocabulary.

## Related Documents
- [[Project Standards]]
- [[YAML Standard]]
- [[Folder Convention]]
- [[Internal Linking Rules]]