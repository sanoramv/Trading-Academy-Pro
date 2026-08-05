# Quiz — Derivatives Cluster

## Header
```
Title: Derivatives (Futures, Options, Greeks, Volatility) Consolidated Quiz
Covers Lessons: [20.01]-[23.06]
Total Questions: 15
Passing Score: 75%
Time Suggested: 30 minutes
```

## Section A — Recall
1. What is the max loss on a long call?
2. What is the max loss on a naked short call?
3. What does Delta measure?
4. What does Theta measure?
5. What is the difference between historical and implied volatility?

## Section B — Application
6. Calculate max profit, max loss, and breakeven for a bull call spread: buy the 100 call for 6, sell the 110 call for 2.
7. An option's Delta is 0.35 and Gamma is 0.04. If the underlying rises 15 points, estimate the new Delta.
8. IV is significantly elevated ahead of a known earnings date. Explain the risk a straddle buyer faces even if the stock moves in the expected direction.
9. You're comparing two Nifty calls: one with Delta 0.60, one with Delta 0.15. Which behaves more like owning the underlying directly, and why?
10. A trader sells an iron condor for a net credit of 90, with wing width of 200. Calculate max profit and max loss.

## Section C — Judgment
11. A trader buys a deep OTM weekly option because "it's so cheap, even a small move is a huge percentage gain." Using `[21.12]`'s framework, evaluate this reasoning.
12. Explain why a defined-risk structure (like an iron condor) still requires active management per `[22.08]`'s case study, rather than being "set and forget."
13. A trader sizes a naked short put the same way they would size an iron condor, using the premium collected as the "stop distance." What is wrong with this approach, per `[26.05]`?

## Answer Key
1. The premium paid. `[21.05]`
2. Theoretically unlimited. `[21.06]`
3. Expected premium change per 1-point move in the underlying. `[22.02]`
4. Expected daily premium change from time decay alone. `[22.04]`
5. Historical is backward-looking; implied is forward-looking, derived from option prices. `[23.01]`
6. Max profit = (110-100) - (6-2) = 6. Max loss = 6-2 = 4. Breakeven = 100+4 = 104. `[21.08]`
7. New Delta ≈ 0.35 + (0.04 × 15) = 0.95 (capped near 1.0 in practice). `[22.03]`
8-13. Open-ended: elevated pre-event IV risks IV crush eroding gains even on a correct directional move (`[22.05]`, `[24.10]`); higher Delta behaves more like the underlying, lower Delta is a smaller, more leveraged bet (`[22.02]`); max profit = 90, max loss = 200-90 = 110 (`[21.10]`); cheap OTM options reflect low probability, not low risk (`[21.12]`); Gamma/Vega risk persists even within defined-risk structures, requiring active monitoring (`[22.07]`, `[22.08]`); undefined-risk positions have no fixed max loss to use as a stop distance, requiring scenario-based sizing instead (`[26.05]`).

## Scoring Guide
| Score | Interpretation |
|---|---|
| 90–100% | Mastery — proceed |
| 75–89% | Passing — proceed, review flagged weak items |
| 50–74% | Not passing — revise flagged lessons before proceeding |
| <50% | Re-teach — do not proceed, schedule remedial lesson |

## Weak Area Logging
Log missed topics into `progress_tracker/` for future re-testing.
