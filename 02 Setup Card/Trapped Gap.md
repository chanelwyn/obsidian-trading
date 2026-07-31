---
title: Trapped Gap
aliases:
  - Stop-Loss Cascade
type: setup
status: active
version: 1.0
phase: Phase-2
tags:
  - setup
  - short
  - gap
source:
  - Master Trading System Rulebook
  - Combined Setup File
---
# Trapped Gap
## Purpose
Short a gap that traps existing long holders. Once key support fails, clustered stop-loss orders create an accelerated downside move.
This setup exploits order-flow imbalance rather than trend continuation alone. 

---
## Qualification
### Market Context
- Bearish catalyst or negative news
- Gap into major support or below it
- Long holders trapped
- High RVOL
- Market and sector supportive
- Adequate liquidity & borrow
### Required Conditions
- Gap positioned at known stop-loss area
- Prior support breaks
- Heavy selling pressure
- Failed bounce
- Buyers unable to reclaim support
- Clear downside room
### Checklist
- [ ] Bearish catalyst confirmed
- [ ] Gap traps prior buyers
- [ ] Key support identified
- [ ] Failed reclaim
- [ ] Tape confirms selling
- [ ] Trigger defined
- [ ] Risk defined before entry
---
## Execution
### Trigger
- Break < trapped support
- Failed reclaim of support
- Tape Conf
- Aggressive sellers lifting bids
### Entry
- Enter after support fails.
- Avoid chasing large extension candles.
- Add only after continuation confirms.
### Stop
Use nearest structural invalidation.
Examples
- Above failed reclaim
- Above gap resistance
- Above VWAP
- Above intraday swing
### Targets
Primary
- Measured move
- Daily support
- Gap continuation
- Panic extension
Management target
- Trail using prior 2m bar.
### Management
- Expect fast expansion after stops trigger.
- Respect the 2m trailing stop.
- Scale according to plan.
- Do not predict the bottom.
### Invalidation
Exit immediately if:
- Support is reclaimed
- Stop cascade fails to develop
- Buyers absorb selling
- Tape turns constructive
- Thesis becomes invalid
---
## Review
### Common Mistakes
- Confusing a normal gap with a trapped gap.
- Shorting before support breaks.
- Ignoring absorption.
- Chasing capitulation.
- Holding after failed reclaim.
- Trading without identifying trapped participants.
### Benchmark Trades
- [[Trapped Gap Examples]]
- [[Stop-Loss Cascade Examples]]
### Coach Notes
> [!warning]
> A gap alone is **not** a Trapped Gap. Trapped participants and a failed reclaim must both be present.
- The edge comes from forced liquidation.
- Wait for trapped buyers to lose control before entering.
- If the stop cascade completes and capitulation develops, the trade may transition into [[Capitulation Reversal Long]].
- Order-flow confirmation is more important than candle appearance.
---
## Related Notes
- [[Capitulation Reversal Long]]
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