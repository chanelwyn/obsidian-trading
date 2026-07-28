---
title: Callout Style Guide
type: standard
status: active
version: 1.0
phase: Phase-1
tags: [standards, callouts]
---
# Callout Style Guide test commit n push

## Purpose
Defines the approved Obsidian callouts for the TradingOS. Callouts should highlight important information, not decorate documents.

## General Rules
- Use Obsidian's native callouts only.
- Use the smallest appropriate callout.
- Keep callout content concise.
- Avoid nesting callouts.
- Do not use consecutive callouts when a normal heading is sufficient.

## Approved Callouts

### Note
Use for supplementary information.
```markdown
> [!note]
> Additional information.
```
### Tip
Use for best practices or recommendations.
```markdown
> [!tip]
> Preferred approach.
```
### Important
Use for rules that should not be overlooked.
```markdown
> [!important]
> Follow this rule at all times.
```
### Warning
Use for common mistakes or actions that may lead to errors.
```markdown
> [!warning]
> Do not modify this template directly.
```
### Danger
Use only for critical rule violations or high-risk actions.
```markdown
> [!danger]
> Never override the Master Trading System Rulebook.
```
### Success
Use to indicate a completed process or expected outcome.
```markdown
> [!success]
> Checklist completed.
```
### Failure
Use when documenting common failure cases.
```markdown
> [!failure]
> Setup invalid due to missing confirmation.
```
### Question
Use to identify items requiring clarification or future review.
```markdown
> [!question]
> Confirm whether this rule applies to all setups.
```
### Todo
Use only for unfinished documentation.
```markdown
> [!todo]
> Insert example chart.
```

Remove all `todo` callouts before a document reaches **Active** status.

## Usage Guidelines

| Callout   | Purpose                |
| --------- | ---------------------- |
| Note      | Additional information |
| Tip       | Recommendation         |
| Important | Critical rule          |
| Warning   | Prevent mistakes       |
| Danger    | High-risk violation    |
| Success   | Completed outcome      |
| Failure   | Failed condition       |
| Question  | Clarification required |
| Todo      | Pending work           |

## When to Use
Use callouts for:
- Critical rules.
- Important reminders.
- Warnings.
- Temporary documentation tasks.
- Small reference notes.

## When Not to Use
Do not use callouts for:
- Normal explanations.
- Entire sections.
- Long paragraphs.
- Lists that belong under headings.
- Decorative formatting.

## Formatting Rules
- One topic per callout.
- Keep content under five lines where practical.
- Do not place tables inside callouts.
- Avoid multiple consecutive callouts.
- Prefer headings when the content is substantial.

## Priority
If multiple callouts could apply, use the highest priority:
1. Danger
2. Warning
3. Important
4. Failure
5. Success
6. Tip
7. Note
8. Question
9. Todo

## Examples
Good:
```markdown
> [!warning]
> Do not duplicate rules across documents.
```

Poor:
```markdown
> [!note]
> This section explains everything about risk management...
> (multiple paragraphs)
```

## Related Documents
- [[Project Standards]]
- [[Formatting Guide]]
- [[Writing Style Guide]]
- [[Templates overview]]