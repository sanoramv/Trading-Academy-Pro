# Drill 5 — Risk Sizing Calculator (By Hand)

> Builds `[25.02]`-`[26.04]`'s position sizing skills by hand.

## Instructions
For each scenario, calculate position size by hand using the correct
formula, then check against the worked answer.

1. Account: ₹6,00,000. Risk: 1%. Entry: ₹450. Stop: ₹432. Calculate position size (shares).
2. Account: ₹10,00,000. Risk: 1.5%. Entry: ₹1,200. Stop: ₹1,150. Calculate position size.
3. Same ₹6,00,000 account, but using ATR-based sizing: ATR = ₹8, stop = 2x ATR, risk = 1%. Calculate position size.
4. A strategy has 55% win rate and a 2:1 payoff ratio. Calculate full Kelly %, then quarter-Kelly %.
5. An iron condor has a known max loss of ₹3,200 per lot. Account risk budget is ₹12,800. Calculate the number of lots.
6. Starting equity ₹5,00,000, apply 1% fixed fractional across three trades with results +₹12,000, -₹6,000, +₹9,000 (recalculate equity after each trade before computing the next risk amount).

## Worked Answers
```
1. Risk Rs = 6,00,000 x 0.01 = 6,000. Stop Distance = 450-432 = 18.
   Position Size = 6,000 / 18 = 333 shares.

2. Risk Rs = 10,00,000 x 0.015 = 15,000. Stop Distance = 1,200-1,150 = 50.
   Position Size = 15,000 / 50 = 300 shares.

3. Risk Rs = 6,00,000 x 0.01 = 6,000. Stop Distance = 2 x 8 = 16.
   Position Size = 6,000 / 16 = 375 shares.

4. Kelly% = W - [(1-W)/R] = 0.55 - [(0.45)/2] = 0.55 - 0.225 = 0.325 (32.5%)
   Quarter-Kelly = 32.5% / 4 = 8.125%

5. Number of Lots = 12,800 / 3,200 = 4 lots.

6. Trade 1: Risk = 5,00,000 x 0.01 = 5,000. Result +12,000.
   New Equity = 5,00,000 + 12,000 = 5,12,000.
   Trade 2: Risk = 5,12,000 x 0.01 = 5,120. Result -6,000.
   New Equity = 5,12,000 - 6,000 = 5,06,000.
   Trade 3: Risk = 5,06,000 x 0.01 = 5,060. Result +9,000.
   Final Equity = 5,06,000 + 9,000 = 5,15,000.
```

## Self-Check Questions
- In Question 6, did you recalculate equity AFTER each trade before computing the next risk amount? This is `[26.02]`'s core compounding mechanism.
- Would you actually deploy full Kelly (32.5%) from Question 4 live? Why not, per `[26.04]`?
- Which formula would you use for a naked short option position, and why does `[26.05]` say this differs from Questions 1-3?

---
*Educational content only. Not investment advice.*
