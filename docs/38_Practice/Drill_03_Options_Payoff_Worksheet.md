# Drill 3 — Options Payoff Worksheet

> Builds `[21.05]`-`[21.10]`'s payoff calculation skills by hand.

## Instructions
For each position below, calculate by hand: max profit, max loss, and
breakeven — then sketch the payoff diagram on paper before checking
the worked answer.

1. Long call: strike 100, premium 5
2. Long put: strike 100, premium 4
3. Short call: strike 100, premium 5
4. Bull call spread: buy 100 call for 6, sell 110 call for 2
5. Bear put spread: buy 100 put for 6, sell 90 put for 2
6. Straddle: buy 100 call for 5, buy 100 put for 4.5
7. Iron condor: short put 90/long put 85, short call 110/long call 115, net credit 3

## Worked Answers
```
1. Long Call (strike 100, premium 5)
   Max Loss = 5 (premium paid)
   Max Profit = Unlimited
   Breakeven = 100 + 5 = 105

2. Long Put (strike 100, premium 4)
   Max Loss = 4
   Max Profit = Large (capped at underlying = 0): 100 - 4 = 96
   Breakeven = 100 - 4 = 96

3. Short Call (strike 100, premium 5)
   Max Loss = Unlimited
   Max Profit = 5 (premium received)
   Breakeven = 100 + 5 = 105 (same as long call, mirrored payoff)

4. Bull Call Spread (buy 100 for 6, sell 110 for 2)
   Net Debit = 6 - 2 = 4
   Max Profit = (110-100) - 4 = 6
   Max Loss = 4
   Breakeven = 100 + 4 = 104

5. Bear Put Spread (buy 100 put for 6, sell 90 put for 2)
   Net Debit = 6 - 2 = 4
   Max Profit = (100-90) - 4 = 6
   Max Loss = 4
   Breakeven = 100 - 4 = 96

6. Straddle (buy 100 call for 5, buy 100 put for 4.5)
   Total Premium = 9.5
   Max Loss = 9.5 (if underlying expires exactly at 100)
   Max Profit = Unlimited (upside) / Large (downside)
   Breakevens = 100 + 9.5 = 109.5 (upper), 100 - 9.5 = 90.5 (lower)

7. Iron Condor (short put 90/long put 85, short call 110/long call 115, net credit 3)
   Max Profit = 3 (net credit)
   Max Loss = Wing Width - Net Credit = 5 - 3 = 2
   Breakevens = 90 - 3 = 87 (lower), 110 + 3 = 113 (upper)
```

## Self-Check Questions
- Did you sketch each payoff diagram BEFORE checking the answer?
- For the spread/condor problems, did you correctly identify the net debit/credit direction?
- Could you explain WHY each formula works, not just apply it mechanically? Revisit `[21.05]`-`[21.10]` if not.

---
*Educational content only. Not investment advice.*
