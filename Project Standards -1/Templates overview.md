---
title: Templates Overview
type: standard
status: active
version: 1.0
phase: Phase-1
tags: [standards, templates]
---
# Templates Overview
## Purpose
Defines the template standard for the TradingOS. Templates provide a consistent structure for recurring documents and should contain layout only, not permanent trading rules.
## General Rules
- One purpose per template.
- Keep templates generic and reusable.
- Do not embed permanent trading rules.
- Update templates only when the document structure changes.
- Every template should follow [[Project Standards]].
## Template Categories
| Category | Purpose |
|----------|---------|
| Standard | Permanent documentation |
| Setup | Trading setup documentation |
| Playbook | Workflow and operating procedures |
| Checklist | Action-based processes |
| Review | Trade and performance reviews |
| Journal | Daily operational notes |
| Dashboard | Navigation and indexes |
| Reference | Structured knowledge |
## Standard Template
Used for permanent documentation.
Sections:
```text
YAML
Purpose
Scope
Main Content
Related Documents
```
## Setup Template
Used for documenting trading setups.
Sections:
```text
YAML
Overview
Requirements
Rules
Examples
Related Documents
```
## Playbook Template
Used for repeatable workflows.
Sections:
```text
YAML
Purpose
Prerequisites
Procedure
Checklist
References
```
## Checklist Template
Used for execution steps.
Sections:
```text
YAML
Purpose
Checklist
Notes
```
Rules:
- Write each step as an action.
- Keep items concise.
- Arrange in execution order.
## Review Template
Used for evaluating completed work.
Sections:
```text
YAML
Summary
Assessment
Findings
Action Items
Related Documents
```
## Journal Template
Used for daily records.
Sections:
```text
YAML
Objectives
Notes
Observations
Review
```
Journals record events only and do not modify permanent documentation.
## Dashboard Template
Used for navigation.
Sections:
```text
YAML
Overview
Quick Links
Indexes
Related Documents
```
Dashboards should primarily contain wikilinks rather than duplicated content.
## Reference Template
Used for structured knowledge.
Sections:
```text
YAML
Definition
Details
References
Related Documents
```
## Template Rules
- Begin with the standard YAML block.
- Use consistent heading hierarchy.
- Keep placeholders concise.
- Remove unused sections before publishing.
- Do not duplicate content across templates.
- Link to authoritative documents instead.
## Naming
According to [[Naming Convention]]
## Storage
Store all templates in the `Templates` folder.
Example:
```text
Templates/
├── Standard Template
├── Setup Card Template
├── Trade Review Template
├── Daily Prep Template
├── Checklist Template
└── Dashboard Template
```
## Maintenance
Review templates when:
- documentation standards change
- recurring document structures change
- a template becomes redundant
- a new document category is introduced 
## Related Documents
- [[Project Standards]]
- [[Markdown Style Guide]]
- [[YAML Standard]]
- [[Naming Convention]]
- [[Folder Convention]]
- [[Internal Linking Rules]]
- [[Writing Style Guide]]