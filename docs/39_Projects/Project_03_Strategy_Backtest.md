# Project 3 — Backtest a Simple Strategy

## Objective
Apply `[29.03]`-`[29.04]`'s backtesting discipline rigorously to one
simple, precisely-defined strategy from Module 24, producing a
trustworthy — not overfit or biased — performance estimate.

## Requirements
1. Choose ONE simple strategy with 2-3 parameters maximum (e.g., `[24.02]`'s trend-following: "price above rising N-day MA, enter on pullback resumption").
2. Gather historical data for a REASONABLY LONG period (ideally 2+ years) across a real instrument.
3. Explicitly check and document your process against `[29.03]`'s pitfall checklist: no look-ahead bias, no survivorship bias (if testing multiple instruments), realistic transaction costs included.
4. Split your data: use the FIRST 70% for any parameter selection/tuning (in-sample), reserve the LAST 30% purely for out-of-sample testing — do not tune using the out-of-sample data.
5. Report in-sample AND out-of-sample results SEPARATELY. Calculate expectancy (`[24.01]`), win rate, average win/loss, and maximum drawdown (`[25.05]`) for both.
6. Write a 1-page honest assessment: does the out-of-sample performance support live deployment, or does the gap between in-sample and out-of-sample suggest overfitting (`[29.04]`)?

## Deliverable Format
A spreadsheet or script with: raw signals generated, trade-by-trade
results, summary statistics (in-sample vs. out-of-sample), and the
1-page written assessment.

## Evaluation Criteria
- [ ] Strategy rules are precisely, unambiguously defined (2-3 parameters max)
- [ ] In-sample and out-of-sample results are reported SEPARATELY, not blended
- [ ] Transaction costs are explicitly included, not assumed zero
- [ ] The written assessment is HONEST about any overfitting gap found — a project reporting "it worked perfectly" without scrutiny fails this criterion
- [ ] Maximum drawdown and its duration are reported alongside average return

## Worked Example Fragment (Illustrative excerpt only)
```
IN-SAMPLE (first 70% of data): Win rate 42%, Expectancy +0.35R, Max DD 18%
OUT-OF-SAMPLE (last 30%): Win rate 38%, Expectancy +0.15R, Max DD 22%

ASSESSMENT: "Out-of-sample expectancy is positive but meaningfully
LOWER than in-sample -- a common, expected pattern, [29.04]. Given
BOTH periods show POSITIVE expectancy and drawdown remains within a
plausible tolerance, this strategy shows REASONABLE (not perfect)
evidence of a genuine, if modest, edge -- warranting cautious,
small-size live testing rather than either full confidence or outright rejection."
```

---
*Educational content only. Not investment advice.*
