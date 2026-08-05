# Quiz — Algorithmic & Quantitative Trading Cluster

## Header
```
Title: Algorithmic & Quantitative Trading Consolidated Quiz
Covers Lessons: [29.01]-[30.08]
Total Questions: 14
Passing Score: 75%
Time Suggested: 25 minutes
```

## Section A — Recall
1. What is algorithmic trading?
2. What is look-ahead bias?
3. What is overfitting (curve-fitting)?
4. How does cointegration differ from correlation?
5. What does VaR estimate?

## Section B — Application
6. A backtest shows an unusually smooth, nearly loss-free equity curve after extensive parameter tuning. What should you suspect, and what test would help confirm it?
7. You're comparing two candidate pairs for a pairs-trading strategy: one shows correlation of 0.85 but no formal cointegration test performed; the other shows a formal, statistically significant cointegration result. Which is the more defensible candidate, and why?
8. A trading bot's risk management logic is embedded within the same function as its signal-generation logic. Identify the architectural risk this creates, referencing a real historical incident.
9. Explain why "95% VaR of ₹1 lakh" does not mean the maximum possible loss is ₹1 lakh.
10. A strategy's autocorrelation is negative at a 3-day lag but positive at a 6-month lag. Explain how both can be true without contradiction.

## Section C — Judgment
11. A retail trader believes they can compete directly with institutional HFT firms using a standard broker API. Evaluate this belief using `[29.08]`'s framework.
12. Explain why "statistical significance alone is insufficient" to validate a quant strategy, per `[30.01]`'s framework.
13. A trader deploys a bot to live trading immediately after a strong backtest result, skipping simulation/paper trading. What risk does this skip, and what real incident illustrates the danger of inadequate testing?
14. Why might a professional quant researcher deliberately prefer a simpler strategy with fewer parameters over a more complex one with marginally better in-sample results?

## Answer Key
1. Computer programs executing trading decisions according to predefined rules, without manual order placement. `[29.01]`
2. Using information in a backtest that wouldn't have been available at the actual simulated trade moment. `[29.03]`
3. Tuning a strategy too precisely to historical data's noise rather than a genuine, persistent pattern. `[29.04]`
4. Cointegration measures a stable relationship between price levels; correlation measures co-movement of returns. `[30.03]`
5. The maximum expected loss over a period at a given confidence level. `[30.07]`
6-14. Open-ended: suspect overfitting, confirm via walk-forward/out-of-sample testing (`[29.04]`); the cointegration-tested pair is more defensible — correlation alone is insufficient for pairs trading (`[30.03]`); combined risk/signal logic risks a signal bug bypassing risk limits, as in Knight Capital's 2012 incident (`[29.06]`); VaR describes a bounded statistical threshold, saying nothing about severity beyond it (`[30.07]`, `[25.07]`); different timescales can show different, non-contradictory autocorrelation signs (`[30.04]`); retail traders lack HFT's specialized, costly infrastructure (co-location, low-latency networks) (`[29.08]`); statistical significance without economic explanation risks capturing coincidence, not genuine edge (`[30.01]`, `[29.04]`); skipping simulation risks live-only failure modes, as Knight Capital's 2012 incident illustrates (`[29.06]`); simpler models are less prone to overfitting and more likely to reflect genuine, persistent, explainable patterns (`[29.04]`).

## Scoring Guide
| Score | Interpretation |
|---|---|
| 90–100% | Mastery — proceed |
| 75–89% | Passing — proceed, review flagged weak items |
| 50–74% | Not passing — revise flagged lessons before proceeding |
| <50% | Re-teach — do not proceed, schedule remedial lesson |

## Weak Area Logging
Log missed topics into `progress_tracker/` for future re-testing.
