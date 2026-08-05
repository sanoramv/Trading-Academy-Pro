# Quant Track Exam

## Header
```
Title: Quant Track Exam
Covers Lessons: [29.01]-[30.08] (Modules 29-30)
Total Questions: 18
Passing Score: 75%
Time Suggested: 40 minutes
```

## Section A — Recall (6 questions)
1. What is the difference between algorithmic and quantitative trading? `[29.01]`, `[30.01]`
2. What is survivorship bias? `[29.03]`
3. What is walk-forward testing? `[29.04]`
4. What is the Kelly Criterion formula? `[26.04]`, `[30.01]`
5. What are the four classic investing factors? `[30.05]`
6. What does VaR estimate, and what is its key limitation? `[30.07]`

## Section B — Application (8 questions)
7. Design a simple backtest checklist ensuring you avoid look-ahead bias, survivorship bias, and unrealistic transaction costs.
8. Given a strategy with 15 tunable parameters tested on only 200 historical trades, assess the overfitting risk and propose a fix.
9. Two stocks show 0.85 correlation but no formal cointegration. Explain why this pair is a weaker pairs-trading candidate than a formally cointegrated pair with lower correlation.
10. Explain how autocorrelation can be negative at a 3-day lag and positive at a 6-month lag for the same instrument, without contradiction.
11. Design a simple trading bot's five-component architecture for a mean-reversion strategy, specifying what each component does.
12. Calculate quarter-Kelly for a strategy with 45% win rate and 2.5 payoff ratio.
13. Explain why a market maker's spread widens during volatile conditions, using the inventory risk concept.
14. A quant researcher finds a statistically significant pattern with no plausible economic explanation. What should they do before deploying it live?

## Section C — Judgment (4 questions)
15. Evaluate: "A backtested strategy with excellent in-sample performance is ready for live deployment." Correct this using this cluster's framework.
16. Explain why retail traders cannot meaningfully compete with institutional HFT, and what quant thinking retail traders CAN meaningfully apply instead.
17. A quant strategy's Sharpe ratio looks excellent, but its Sortino ratio is much lower. What does this divergence suggest about the strategy's return distribution?
18. Defend or critique: "Statistical significance alone is sufficient to validate a trading strategy."

## Answer Key
Question 12: Kelly% = 0.45 - (0.55/2.5) = 0.45 - 0.22 = 0.23 (23% full
Kelly); quarter-Kelly = 5.75%. Grade remaining answers against each
cited lesson's specific reasoning.

## Scoring Guide
| Score | Interpretation |
|---|---|
| 90–100% | Mastery — quant track complete |
| 75–89% | Passing — proceed, review flagged weak items |
| 50–74% | Not passing — revise flagged Modules 29-30 lessons |
| <50% | Re-teach — do not proceed |

## Weak Area Logging
Log missed topics into `progress_tracker/`.
