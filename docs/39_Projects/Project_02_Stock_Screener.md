# Project 2 — Build a Stock Screener

## Objective
Apply Module 08-09's fundamental analysis and `[30.05]`'s factor
investing framework by building a working screening tool (spreadsheet
or simple script) that filters a stock universe by specific,
quantifiable criteria.

## Requirements
1. Choose a universe (e.g., Nifty 500, or any accessible index constituent list).
2. Define at least THREE quantifiable screening criteria drawn from this academy, for example:
   - A value criterion (P/E or P/B below a threshold, `[09.02]`)
   - A quality criterion (ROE above a threshold, debt-to-equity below a threshold, `[08.03]`, `[08.04]`)
   - A momentum criterion (trailing 6-month return above a threshold, `[24.08]`)
3. Pull real, current data for your chosen universe (via any accessible source — broker platform, financial data website, or provided dataset).
4. Apply your screen and produce a ranked shortlist.
5. Write a 1-page rationale explaining WHY each criterion was chosen and what it's meant to capture.

## Deliverable Format
A spreadsheet (or script + output) containing: the full universe with raw data, your screening formulas applied, and the resulting shortlist — plus the 1-page rationale document.

## Evaluation Criteria
- [ ] At least three genuinely different, quantifiable criteria used (not just one repeated in different forms)
- [ ] Criteria are drawn from and reference specific lessons (`[08.03]`, `[09.02]`, `[24.08]`, etc.)
- [ ] The screen was applied to REAL, current data — not hypothetical numbers
- [ ] Rationale explains the ECONOMIC reasoning behind each criterion, not just "this is a common metric"
- [ ] You checked for `[27.04]`'s correlation-clustering risk in your shortlist (are the results all one sector?)

## Worked Example Fragment (Illustrative excerpt only)
```
CRITERION 1 (Value): P/E < sector median
CRITERION 2 (Quality): ROE > 15%, Debt/Equity < 0.5
CRITERION 3 (Momentum): Trailing 6-month return > Nifty 500's median return

RATIONALE: "Combining value and momentum specifically counters each
factor's individual weakness -- value alone can catch 'cheap for a
reason' traps ([09.06]), momentum alone can catch overextended stocks
-- requiring BOTH filters raises the bar for inclusion."
```

---
*Educational content only. Not investment advice.*
