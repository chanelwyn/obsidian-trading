---
title: Trade Execution
aliases:
  - Execution Playbook
tags:
  - trading/live
  - execution
type: operating-manual
status: active
created:
updated:
---
# Trade Execution
> [!summary]
> Objective: Execute only valid setups with predefined risk and rule-based management.
---
## Execution Flow
```text
Setup
    ↓
Validate
    ↓
Entry
    ↓
Risk
    ↓
Manage
    ↓
Exit
```
---
## 1. Setup Validation
> [!check]- Before Any Order
- [ ] Market regime supports the setup
- [ ] Daily bias confirmed
- [ ] Setup matches playbook
- [ ] Setup grade assigned
- [ ] News checked
- [ ] Room to target exists
> [!note]
> Trade the setup, not the ticker.
Reference:
- [[Combined Setup File]]
---
## 2. Entry Checklist
> [!check]- Trigger
- [ ] Entry trigger confirmed
- [ ] No anticipation
- [ ] Tape supports the trigger (if required)
- [ ] Volume confirms (if required)
- [ ] Risk acceptable
Do **not** enter if:
- Trigger not confirmed
- Chasing price
- Missing required confirmation
- Risk undefined
---
## 3. Position Risk
> [!check]- Before Clicking Buy / Sell
- [ ] Structural stop defined
- [ ] Position size calculated
- [ ] Maximum loss acceptable
- [ ] R:R acceptable
Reference:
- [[Position Sizing]]
---
## 4. Trade Management
> [!check]- During Trade
- [ ] Thesis still valid
- [ ] Follow predefined stop
- [ ] Scale only if planned
- [ ] Trail according to setup
- [ ] Never widen risk
> [!important]
>
> Manage the trade, not the P&L.
---
## 5. Exit Rules
Exit when:
- [ ] Stop reached
- [ ] Target reached
- [ ] Setup invalidated
- [ ] Rule-based trailing stop triggered
- [ ] Market context changes
Never exit because of:
- Fear
- Hope
- Unrealised P&L
- Social media
- Impulse
---
## 6. Kill Switch
Stop trading immediately if:
- [ ] Daily loss limit reached
- [ ] Multiple rule violations
- [ ] Platform failure
- [ ] Emotional control lost
- [ ] Market no longer fits playbook
Reference:
- [[Risk & Discipline]]
---
## Non-Negotiables
> [!important]
>
> - No setup → No trade.
> - No trigger → No entry.
> - No stop → No position.
> - No discipline → Stop trading.
> - Protect capital first.
---
## Post-Trade
After every trade:
- [ ] Screenshot saved
- [ ] Notes recorded
- [ ] Rule violations documented
- [ ] Journal updated
Reference:
- [[Review & Improvement]]
---
### Navigation
← [[Daily Operating System]]
→ [[Review & Improvement]]