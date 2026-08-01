---
title: Trade Review
type: review
status: active
version: 1.0
phase: Phase-4
tags:
  - review
  - execution
  - performance
source:
  - Master Trading System Rulebook
  - Combined Setup File
  - Trading Coach Specification
  - Trade Scoring Rubric
  - Trade Review Intake Template
---

# Trade Review

> [!important]
> Evaluate execution against the documented trading system. Review the process, not the P&L.

## Purpose

Review every completed trade to:

- Validate setup quality
- Evaluate execution quality
- Identify rule breaches
- Capture actionable improvements
- Improve consistency over time

---

## Review Workflow

```text
Complete Trade
      ↓
Collect Trade Data
      ↓
Validate Setup
      ↓
Review Execution
      ↓
Score Trade
      ↓
Identify Rule Breaches
      ↓
Record Lessons
      ↓
Update Improvement Tracker (if recurring)
```

---

## Pre-Review Checklist

- [ ] Trade completed
- [ ] Entry and exit recorded
- [ ] Screenshots saved
- [ ] Market context available
- [ ] Trade thesis documented
- [ ] Review completed within 24 hours

---

## Review Process

### 1. Validate Setup

Verify:

- Correct setup selected
- Required conditions satisfied
- Market regime aligned
- Setup grade assigned correctly

Reference:

- [[Combined Setup File]]

---

### 2. Review Execution

Evaluate:

- Entry timing
- Trigger quality
- Position sizing
- Stop placement
- Trade management
- Exit execution

Reference:

- [[Trading Coach Specification]]
- [[Trade Scoring Rubric]]

---

### 3. Context Review

Check:

- Market regime
- Sector strength
- News
- Daily structure
- Intraday context

---

### 4. Rule Compliance

Identify every breached rule.

Reference:

- [[Master Trading System Rulebook]]

If no breach exists, record:

```text
None
```

---

### 5. Trade Classification

Classify independently of profit.

| Classification | Description |
|---------------|-------------|
| Good Win | Correct process + profitable |
| Good Loss | Correct process + losing outcome |
| Bad Win | Poor process + profitable outcome |
| Bad Loss | Poor process + losing outcome |

---

### 6. Action Items

Record only improvements that affect future execution.

Good examples:

- Wait for trigger confirmation.
- Reduce size on B-grade setups.
- Respect trailing stop.
- Skip C-grade trades.

Avoid generic comments.

---

## Review Output

Every review should contain:

1. Verdict
2. Setup Assessment
3. Execution Assessment
4. Context Assessment
5. What Was Good
6. What Was Wrong
7. Rule Breaches
8. Next Trade Instruction

Use the [[Trade Review Intake Template]] and [[Trading Coach Specification]] for the review format.

---

## Escalation Rules

Update [[TICK]] when:

- The same mistake repeats.
- A rule breach becomes recurring.
- A weakness affects multiple trades.

Otherwise, keep the lesson within the individual review.

---

## Do Not

- Judge quality by P&L alone.
- Modify permanent trading rules.
- Ignore missing trade information.
- Justify rule violations.
- Duplicate setup rules.

---

## Related Documents

- [[Master Trading System Rulebook]]
- [[Combined Setup File]]
- [[Trading Coach Specification]]
- [[Trade Scoring Rubric]]
- [[Trade Review Intake Template]]
- [[TICK]]
- [[Daily Journal]]
- [[Performance Dashboard]]