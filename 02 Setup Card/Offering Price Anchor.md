---
title: Offering Price Anchor
aliases:
  - Offering Reversal
type: setup
status: active
version: 1.0
phase: Phase-2
tags:
  - setup
  - reversal
  - long
  - short
source:
  - Master Trading System Rulebook
  - Combined Setup File
---
# Offering Price Anchor
## Purpose
Trade the offering price as the institutional equilibrium level.
Stocks trading significantly above the offering price tend to mean-revert towards it. Once the offering price is reached and accepted, the short thesis ends and a long reversal may develop.

---
## Qualification
### Market Context
- Recent secondary offering
- Offering price known
- High RVOL
- Elevated volatility
- Strong liquidity
- Clear institutional participation
### Required Conditions
#### Short Phase
- Opens well above offering price
- Price trending toward offering
- Sellers remain in control
- Clear downside room
#### Long Phase
- Offering price reached
- Selling pressure exhausted
- Price stabilises
- Buyers absorb supply
- Reversal begins
### Checklist
- [ ] Offering price identified
- [ ] News verified
- [ ] Current price materially above offering
- [ ] Short thesis valid
- [ ] Offering level marked
- [ ] Trigger defined
- [ ] Risk defined before entry
---
## Execution
### Trigger
**Short**
- Break < intraday support
- Continuation toward offering
- Tape Conf
**Long**
- Offering price holds
- Break > reversal candle H
- Tape Conf
### Entry
- Short only while price remains above the offering price.
- Cover into the offering price.
- Consider long only after clear reversal confirmation.
### Stop
**Short**
- Above failed breakdown
- Above VWAP
- Above swing H
**Long**
- Below offering price
- Below reversal L
- Below support
### Targets
**Short**
- Offering price (primary target)
**Long**
- VWAP
- EMA
- Gap fill
- Intraday resistance
Management target
- Trail using prior 2m bar.
### Management
- Treat the offering price as equilibrium.
- Do not continue shorting once the offering price is reached.
- Wait for confirmation before reversing long.
- Manage the new long independently of the previous short.
### Invalidation
Exit immediately if:
- Short thesis fails above offering
- Offering level rejected unexpectedly
- Reversal loses momentum
- New information changes valuation
- Tape contradicts the thesis
---
## Review
### Common Mistakes
- Shorting through the offering price.
- Guessing the reversal before confirmation.
- Treating the offering price as ordinary support.
- Ignoring institutional equilibrium.
- Combining the short and long into one unmanaged trade.
- Forgetting to verify the actual offering price.
### Benchmark Trades
- [[Offering Price Examples]]
- [[Offering Reversal Examples]]
### Coach Notes
> [!warning]
> Offering price reached → Stop all short activity.
- The offering price represents institutional fair value, not just another support level.
- The short and long are **two separate trades**.
- Confirmation is required before initiating the long reversal.
- This setup frequently follows an [[Opening Drive]] after a secondary offering.
---
## Related Notes
- [[Opening Drive]]
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