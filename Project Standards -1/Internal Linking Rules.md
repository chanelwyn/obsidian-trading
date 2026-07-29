---
title: Internal Linking Rules
type: standard
status: active
version: 1.0
phase: Phase-1
tags: [standards, linking]
---

# Internal Linking Rules

## Purpose
Defines the wikilinking standard for the TradingOS. Internal links are the primary navigation method throughout the vault.

## General Rules
- Prefer wikilinks over folder navigation.
- Link to the authoritative document.
- Do not duplicate information.
- Every permanent document should link to related documents.
- Broken links are not permitted.
- Prefer section links within the same document before creating a new note

## Standard Link

```markdown
[[Risk Management]]
```

Use when referring to an entire document.

## Heading Link

```markdown
[[Risk Management#Position Sizing]]
```

Use when referencing a specific section.

## Block Link

```markdown
[[Risk Management#^position-sizing]]
```

Use only when referencing a reusable block of content.

## Alias Link

```markdown
[[Capitulation Long|Capi Long]]
```

Use aliases only to improve readability.

## Embedded Note

```markdown
![[Pre-Trade Checklist]]
```

Embed only when the content should always remain synchronised with the source document.

## Embedded Section

```markdown
![[Risk Management#Daily Loss Limit]]
```

Use to display a specific section without duplicating it.

## Related Documents
Every permanent document should end with a related documents section.

Example:

```markdown
## Related Documents
- [[Risk Management]]
- [[Position Sizing]]
- [[Trade Review Checklist]]
```

Include only documents with a meaningful relationship.

## Linking Principles

### Link the Source
Correct:

```markdown
See [[Risk Management]].
```

Incorrect:

```markdown
Copy the entire Risk Management rules here.
```

### One Source of Truth
Each concept should have one authoritative document.

Reference it everywhere else using a wikilink.

### Keep Links Relevant
Every link should help the reader.

Avoid excessive or unnecessary links.

## When to Link
Create links for:
- Rules
- Setups
- Playbooks
- Standards
- Checklists
- Templates
- Dashboards
- Glossary terms

## Do Not Link
Avoid linking:
- Every occurrence of the same word.
- Common trading terminology.
- Dates.
- YAML fields.
- Tags.
- Folder names.

## Link Frequency
Recommended:
- First mention of an important concept.
- Section summaries.
- Related Documents section.

Avoid linking the same document repeatedly within a short section.

## File Renaming
When renaming a file:
- Preserve existing wikilinks.
- Update aliases if required.
- Do not create duplicate documents.

## Folder Independence
Links must never rely on folder paths.

Correct:

```markdown
[[Capitulation Long]]
```

Incorrect:

```markdown
[[Setups/Capitulation Long]]
```

## Dashboards
Dashboard documents should use wikilinks to organise content rather than duplicate it.

Example:

```markdown
# Setups

- [[Capitulation Long]]
- [[Bouncy Ball Short]]
- [[Opening Drive]]
```

## Broken Links
Broken links should be resolved immediately by:
- Correcting the target.
- Renaming the link.
- Removing obsolete references.

Do not leave placeholder links in permanent documentation.

## Maintenance
Review links periodically to:
- Remove obsolete references.
- Eliminate duplicate links.
- Verify renamed documents.
- Maintain logical navigation.

## Related Documents
- [[Project Standards]]
- [[Formatting Guide]]
- [[Naming Convention]]
- [[Folder Convention]]
- [[Tag Convention]]
- [[Templates overview]]