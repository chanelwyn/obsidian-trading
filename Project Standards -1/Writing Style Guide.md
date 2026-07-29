---
title: Writing Style Guide
type: standard
status: active
version: 1.0
phase: Phase-1
tags: [standards, writing]
---

# Writing Style Guide

## Purpose
Defines the writing standard for every TradingOS document. The objective is consistency, clarity and long-term maintainability.

## Core Principles
- Write for precision, not persuasion.
- Be concise.
- One idea per paragraph.
- Prefer facts over opinions.
- Keep documents easy to scan.
- Every sentence should add value.

## Writing Tone
Use a professional, technical and objective tone.

Write:
- Clearly.
- Directly.
- Consistently.
- Without emotion.

Avoid:
- Storytelling.
- Motivational language.
- Personal opinions.
- Humour.
- Marketing language.

## Voice
Use active voice whenever practical.

Good:

```text
Review the setup before entry.
```

Avoid:

```text
The setup should be reviewed before entry.
```

## Language
Prefer:
- Short sentences.
- Specific wording.
- Consistent terminology.
- Bullets over paragraphs
- operational writing
- remove filler
- one-screen as first
- every heading must add value

Avoid:
- Ambiguous language.
- Filler words.
- Repetition.
- Unnecessary adjectives.

## Terminology
Use the same term for the same concept throughout the vault.

Correct:

```text
Trade Review
```

Not:

```text
Trade Analysis
Trade Evaluation
Trade Assessment
```

unless they represent different concepts.

## Rules
Rules should be written as instructions.

Good:

```text
Exit immediately if the setup becomes invalid.
```

Avoid:

```text
You may consider exiting.
```

## Definitions
Define new terms before using them extensively.

Example:

```text
Setup Validity: The conditions required before a trade may be executed.
```

## Lists
Use bullet lists for:
- Rules
- Requirements
- Conditions
- Features

Use numbered lists only when order matters.

## Tables
Use tables only for:
- Comparisons
- Status values
- Field definitions
- Structured references

Avoid tables containing long paragraphs.

## Examples
Include examples only when they improve understanding.

Keep examples:
- Short
- Relevant
- Easy to recognise

## Consistency
Maintain consistent:
- Terminology
- Capitalisation
- Formatting
- Heading structure
- List style

Do not alternate between different writing styles.

## Capitalisation

Use Title Case for:
- Document titles
- Folder names
- Standards
- Setup names

Use sentence case for:
- Paragraphs
- Lists
- Explanations

## Abbreviations
Use recognised trading abbreviations only.

Examples:

```text
VWAP
EMA
SSR
SPY
QQQ
```

Spell uncommon terms in full on first use.

## Numbers
Use numerals for:
- Dates
- Versions
- Percentages
- Prices
- Quantities

Example:

```text
Version 1.2
2% risk
10 EMA
```

## References
Reference other documents using wikilinks.

Correct:

```markdown
See [[Risk Management]].
```

Do not duplicate information from another document.

## Avoid
- Long introductions.
- Repeated explanations.
- Decorative formatting.
- Large blocks of text.
- Excessive callouts.
- Unnecessary quotations.

## Review Checklist
Before publishing a permanent document, verify:
- Terminology is consistent.
- Rules are unambiguous.
- Grammar is correct.
- Formatting follows the standards.
- Links are valid.
- No duplicate information exists.
- YAML is complete.

## Related Documents
- [[Project Standards]]
- [[Formatting Guide]]
- [[YAML Standard]]
- [[Callout Style Guide]]
- [[Internal Linking Rules]]