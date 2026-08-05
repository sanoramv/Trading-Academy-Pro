# Project 4 — Build a Personal Risk Dashboard

## Objective
Apply Modules 25-27 to build a working dashboard (spreadsheet is
sufficient) that gives you, at a glance, your current portfolio's risk
exposure — operationalizing `[25.08]`'s rulebook into a live monitoring tool.

## Requirements
Your dashboard must display, for a real or hypothetical portfolio of at least 5 positions:
1. **Per-position risk** — current risk-per-trade (`[25.02]`) as a % of account, for each open position.
2. **Aggregate risk** — total risk across all open positions combined.
3. **Correlation clustering** — group positions by sector/macro driver (`[25.06]`) and show total risk PER CLUSTER, not just per position.
4. **Drawdown tracker** — current account value vs. all-time-high, with drawdown % calculated live (`[25.05]`).
5. **Portfolio allocation view** — current asset-class allocation (equity/debt/cash/derivatives) vs. your target allocation (`[27.02]`).
6. **A single "STATUS" flag** — a simple visual (color/text) indicator showing whether any rule (per-trade limit, cluster limit, drawdown trigger) is currently breached.

## Deliverable Format
A spreadsheet with live formulas (not hardcoded numbers) so that
updating a position automatically recalculates every dashboard section.

## Evaluation Criteria
- [ ] All six required sections are present and functional
- [ ] Cluster grouping reflects genuine correlation logic (`[25.06]`), not just alphabetical sector labels
- [ ] Drawdown percentage is calculated via a live formula, not manually entered
- [ ] The STATUS flag correctly triggers when a rule is breached (test it by entering a deliberately oversized position)
- [ ] The dashboard would genuinely be usable daily, not just as a one-time exercise

## Worked Example Fragment (Illustrative excerpt only)
```
CLUSTER: "Indian Banking" (HDFC Bank + ICICI Bank + Axis Bank positions)
  Position 1 Risk: 1.0%  |  Position 2 Risk: 0.8%  |  Position 3 Risk: 1.0%
  CLUSTER TOTAL: 2.8% (flagged RED if cluster limit is set at 3%,
  since a single sector shock could hit ALL THREE simultaneously, [25.06])

DRAWDOWN TRACKER: Current Equity 9,40,000 / All-Time-High 10,00,000
  = -6.0% drawdown (formula: =(ATH-Current)/ATH)
```

---
*Educational content only. Not investment advice.*
