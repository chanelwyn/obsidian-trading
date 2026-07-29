---
title: Notation Standard
type: standard
status: active
version: 1.0
phase: Phase-1
tags: [standards, notation]
---
# Notation Standard
## Purpose
Defines the standard notation, symbols and abbreviations used throughout the TradingOS. Every document should maximise information density while maintaining clarity.
## Core Principle
Prefer:
1. Symbol
2. Number
3. Abbreviation
4. Word
Example:
```text
RVOL >5x
```
Not:
```text
Relative Volume is greater than five times.
```
## General Rules
- Use recognised trading abbreviations.
- Prefer symbols over words where meaning remains clear.
- Keep notation consistent across the vault.
- Do not invent abbreviations without documenting them here.
- If ambiguity exists, write the full term.
## Standard Symbols
| Meaning | Standard | Example |
|---------|:--------:|---------|
| Greater than | `>` | RVOL >5x |
| Less than | `<` | Risk <1R |
| Greater / Equal | `>=` | RR >=2 |
| Less / Equal | `<=` | Gap <=5% |
| Equal | `=` | Risk =0.5R |
| Not Equal | `!=` | Setup != Valid |
| Approximately | `≈` | Price ≈ VWAP |
| Change / Delta | `Δ` | ΔVol +35% |
| Increase | `↑` | ↑Vol |
| Decrease | `↓` | ↓Vol |
| Then / Process | `→` | PB → Entry |
| At | `@` | Reject @ VWAP |
| Plus | `+` | Trigger + Tape Conf |
| Minus | `-` | Gap - News |
| Multiply | `x` | RVOL >5x |
| Percentage | `%` | Gap >20% |
| And | `&` | Price & Vol |
## Time Notation
| Standard | Meaning |
|----------|---------|
| `1m` | 1-minute |
| `2m` | 2-minute |
| `5m` | 5-minute |
| `15m` | 15-minute |
| `1h` | 1-hour |
| `D` | Daily |
| `W` | Weekly |
| `M` | Monthly |
| `YTD` | Year-to-Date |
Examples:
```text
2m PB
5m Trend
D Support
YTD H
```
## Price & Volume
| Standard | Meaning |
|----------|---------|
| H | High |
| L | Low |
| O | Open |
| C | Close |
| Vol | Volume |
| RVOL | Relative Volume |
| ADV | Average Daily Volume |
| ΔVol | Volume Change |
Examples:
```text
RVOL >5x
ΔVol +40%
Vol ≈ Prev Vol
```
## Trading Abbreviations
| Standard | Meaning |
|----------|---------|
| PM | Premarket |
| AH | After Hours |
| RTH | Regular Trading Hours |
| Multi-D | Multi-Day |
| Prev | Previous |
| EMA | Exponential Moving Average |
| VWAP | Volume Weighted Average Price |
| PDH | Previous Day High |
| PDL | Previous Day Low |
| YTD H | Year-to-Date High |
| YTD L | Year-to-Date Low |
## Execution Abbreviations
| Standard | Meaning |
|----------|---------|
| PB | Pullback |
| BO | Breakout |
| BD | Breakdown |
| Cons | Consolidation |
| Conf | Confirmation |
| Tape | Tape Reading |
| ET | Entry Trigger |
| SL | Stop Loss |
| PT | Profit Target |
| RR | Risk / Reward |
| Pos | Position |
| Mom | Momentum |
## Compression Rules
Prefer:
```text
RVOL >5x
Gap >20%
PB ↓Vol
Price ≈ VWAP
Reject @ PDH
ΔVol +30%
```
Instead of:
```text
Relative volume is greater than five times.
The gap is larger than twenty percent.
The pullback occurred on decreasing volume.
The price is approximately equal to VWAP.
The stock rejected the previous day's high.
Volume increased by thirty percent.
```
## Workflow Examples
Preferred:
```text
Multi-D ↑
PM BO Fail
Reject @ PDH
PB ↓Vol
RVOL >5x
Entry > Trigger + Tape Conf
SL = Prev Swing
PT1 = 2R
Trail = 2m Low
```
## Avoid
- Personal abbreviations.
- Multiple abbreviations for the same concept.
- Long prose when notation is sufficient.
- Mixing full terms and abbreviations inconsistently.
- Symbols that are not defined in this document.
## Maintenance
When introducing new notation:
- Verify it is unambiguous.
- Add it to this document.
- Use it consistently throughout the vault.
- Avoid creating synonyms.
## Related Documents
- [[Project Standards]]
- [[Writing Style Guide]]
- [[Markdown Style Guide]]
- [[Naming Convention]]