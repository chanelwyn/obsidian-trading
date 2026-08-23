---
title: Capitulation Reversal Long
type: setup
status: active
version: 1.0
phase: Phase-2
tags:
  - setup
  - long
  - reversal
source:
  - Master Trading System Rulebook
  - Combined Setup File
---
### Capitulation Reversal Long
| D                  | Mkt                      | Intra-D           |
| ------------------ | ------------------------ | ----------------- |
| Overextend         | Sector support reversion | 2* Bar length     |
| ↑Rvol              |                          | 2* Vol            |
| Major S/R nearby   |                          | Far from EMA/VWAP |
| X News → Over-news |                          | Tape breakthru    |
|                    |                          | 2min bar H/L      |

---
## Execution
### Trigger
- Break > first reversal candle H
- Higher low confirmed
- Tape Cfm
- Buyers lifting offers
### Entry
- Enter only after confirmation.
- Never average into a falling knife.
- Add only after momentum confirms.
### Stop
Use nearest structural invalidation.
Examples:
- Below capitulation low
- Below reversal swing
- Below support
### Targets
Primary
- VWAP
- EMA
- Gap fill
- Intraday resistance
Management target
- Scale into strength.
- Trail remaining position using prior 2m bar.
### Management
- Immediate momentum is expected.
- Reduce exposure if momentum disappears.
- Scale according to plan.
- Respect predefined risk.
### Invalidation
Exit immediately if:
- Capitulation low fails
- Reversal stalls after entry
- Sellers regain control
- Fresh bearish news appears
- Tape rejects higher prices
---
## Review
### Common Mistakes
- Catching the falling knife.
- No capitulation volume.
- Entering before confirmation.
- Averaging down.
- Holding a stalled reversal.
- Confusing a dead-cat bounce with a true reversal.
### Benchmark Trades
- [[ASML 2024-10-15]]
- [[ZONE 2025-11-11]]
- [[Capitulation Reversal Examples]]
### Coach Notes
> [!warning]
> No ≥2x volume spike → No Capitulation Reversal Long.
- Wait for the **right side of the V**.
- This is a mean-reversion setup, not a trend-following trade.
- If the bounce stalls immediately after entry, exit quickly.
- Context overrides pattern; major news may invalidate or strengthen the setup.
---
## Related Notes
- [[Combined Setup File]]
- [[Master Trading System Rulebook]]
- [[Risk Management]]
- [[Entry Rules]]
- [[Exit Rules]]
- [[Tape Reading]]
- [[Trading Constitution]]
- [[Trade Review Template]]
## Rules
- Follow only the setup-specific rules defined in [[Combined Setup File]].
- General execution, risk and psychology rules remain in their authoritative documents.