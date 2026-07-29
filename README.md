---
title: README
type: guide
status: active
version: 1.0
phase: Phase-0
tags:
  - guide
  - architecture
---
# TradingOS

## Purpose

- Centralise trading knowledge.
- Standardise trading workflows.
- Reduce decision fatigue.
- Separate permanent knowledge from daily operations.
- Maintain a single source of truth.
- Support continuous system improvement.

## Core Principles

- One concept per document.
- One source of truth.
- Link instead of duplicate.
- Folders organise; wikilinks navigate.
- Templates standardise recurring work.
- Permanent knowledge changes slowly.
- Journals record observations, not rules.

## Vault Structure

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

## Trading Workflow

```text
Preparation
    ↓
Market Analysis
    ↓
Trade Planning
    ↓
Live Execution
    ↓
Replay
    ↓
Trade Review
    ↓
Journal
    ↓
System Improvement
```

## Modules

### Standards
Permanent documentation governing the vault.
- [[Project Standards]]
- [[YAML Standard]]
- [[Formatting Guide]]
- [[Naming Convention]]

### Rulebook
Authoritative trading knowledge.
- [[Master Trading System Rulebook]]
- [[Combined Setup File]]
- [[Trading Coach Specification]]
- [[Trade Scoring Rubric]]

### Setups
One document per trading setup containing context, requirements, triggers, risk, exits, and examples.

### Playbooks
Operational procedures such as market preparation, execution routines, and replay workflows.

### Reviews
Completed trade, weekly, and monthly performance reviews.

### Journal
Operational observations and reflections. Journals never modify permanent documentation.

### Templates
Reusable document structures for recurring workflows.

## Navigation

TradingOS is designed around Obsidian-native navigation:
- Wikilinks
- Backlinks
- Search
- Graph View
- [[Home]]

Folders exist only for organisation.

## Source of Truth

Documentation follows this priority:

1. Master Trading System Rulebook
2. Combined Setup File
3. Trading Coach Specification
4. Trade Scoring Rubric
5. Trade Review Intake Template
6. Standards
7. Templates
8. Journals

Higher-priority documents always override lower-priority documents.

## Getting Started

1. Open [[Home]].
2. Complete pre-market preparation.
3. Execute only documented setups.
4. Record every trade.
5. Complete replay and review.
6. Update the journal.

## Requirements

Recommended Obsidian features:
- Wikilinks
- Backlinks
- Properties (YAML)
- Templates
- Graph View

No third-party plugins are required.

## Design Goals

TradingOS is designed to be:
- Obsidian-native
- Modular
- Deterministic
- Searchable
- Scalable
- Maintainable

## Related Documents

- [[Home]]
- [[Vault Guide]]
- [[Project Standards]]
- [[Master Trading System Rulebook]]