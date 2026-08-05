# Derivatives Proficiency Exam

## Header
```
Title: Derivatives Proficiency
Covers Lessons: [20.01]-[23.06] (Modules 20-23)
Total Questions: 20
Passing Score: 75%
Time Suggested: 40 minutes
```

## Section A — Recall (8 questions)
1. What is the difference between a futures contract and an option? `[20.01]`, `[21.01]`
2. What is contango vs. backwardation? `[20.05]`
3. What is the max loss on a long put? `[21.05]`
4. What is the max loss on a naked short put? `[21.06]`
5. What does Gamma measure? `[22.03]`
6. What does Vega measure? `[22.05]`
7. What is volatility skew? `[23.04]`
8. What is India VIX? `[23.02]`

## Section B — Application (8 questions)
9. Calculate max profit, max loss, and breakeven for an iron condor: short put 90/long put 85, short call 110/long call 115, net credit 3.
10. An option's Delta is 0.40. Estimate the expected premium change if the underlying rises 50 points.
11. IV is elevated ahead of a known event. Explain the risk this poses to a straddle buyer even if the direction is correct.
12. Compare a bull call spread's risk-reward to a plain long call's — what's the trade-off?
13. A trader sells a naked call believing the maximum loss "can't be that bad." Correct this using `[21.06]`'s framework.
14. Explain the theta decay trap using a specific numeric example.
15. Using Greeks, explain why a short ATM iron butterfly close to expiry is simultaneously income-generating (Theta) and risky (Gamma).
16. A trader wants to size a naked short put position. Why can't they use the standard Position Size = Risk ÷ Stop Distance formula directly?

## Section C — Judgment (4 questions)
17. Evaluate: "Buying cheap, far-OTM options is a low-risk way to speculate." Use `[21.12]`'s framework.
18. A trader holds a long-volatility ETP for two years, expecting it to track VIX. Explain why this expectation is likely to be disappointed, per `[23.06]`.
19. Explain why active Greeks-based management matters even for defined-risk structures like iron condors, per `[22.08]`'s case study.
20. A trader ignores IV level entirely when choosing between buying and selling options. What risk does this create?

## Answer Key
Grade against the specific reasoning in each cited lesson; question 9's
numeric answer: Max Profit = 3, Max Loss = 5-3 = 2.

## Scoring Guide
| Score | Interpretation |
|---|---|
| 90–100% | Mastery — proceed to Module 24 |
| 75–89% | Passing — proceed, review flagged weak items |
| 50–74% | Not passing — revise flagged Modules 20-23 lessons |
| <50% | Re-teach — do not proceed |

## Weak Area Logging
Log missed topics into `progress_tracker/` before advancing.
