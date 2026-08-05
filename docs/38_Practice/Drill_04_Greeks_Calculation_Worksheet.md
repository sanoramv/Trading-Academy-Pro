# Drill 4 — Greeks Calculation Worksheet

> Builds `[22.02]`-`[22.06]`'s Greeks estimation skills by hand.

## Instructions
For each scenario, estimate the requested value by hand using this
academy's simplified estimation formulas, then check against the worked answer.

1. A call has Delta 0.45. The underlying rises 30 points. Estimate the expected premium change.
2. A call has Delta 0.50 and Gamma 0.04. The underlying rises 20 points. Estimate the new Delta.
3. A long option has Theta -3.20. Estimate the cumulative premium loss from time decay alone over 4 days (holding Theta roughly constant, a simplification).
4. A long option has Vega 12. IV falls from 20% to 15%. Estimate the premium change from this Vega effect alone.
5. Given the same option's Delta (0.45, from Q1) and Vega (12, from Q4) — if the underlying ALSO rises 30 points AND IV falls 5 points simultaneously, estimate the NET premium change combining both effects.

## Worked Answers
```
1. Expected Premium Change ~= Delta x Underlying Move
   = 0.45 x 30 = +13.5

2. New Delta ~= Old Delta + (Gamma x Underlying Move)
   = 0.50 + (0.04 x 20) = 0.50 + 0.80 = 1.30
   (capped near 1.0 in practice -- deep ITM Delta ceiling)
   REALISTIC estimate: Delta approaches ~0.95-1.00

3. Cumulative Theta Loss ~= Theta x Days
   = -3.20 x 4 = -12.80 (a loss of 12.80 in premium from time alone)

4. Expected Premium Change ~= Vega x IV Change
   = 12 x (-5) = -60 (a loss of 60 in premium from Vega/IV decline)

5. NET Premium Change ~= Delta effect + Vega effect
   = (0.45 x 30) + (12 x -5) = 13.5 + (-60) = -46.5
   (a NET LOSS despite the underlying moving favorably --
   illustrates [21.12]'s theta decay trap / IV crush risk directly:
   a favorable Delta move can still be OVERWHELMED by an unfavorable
   Vega move)
```

## Self-Check Questions
- Did Question 5 surprise you? This is exactly the mechanism `[22.05]`'s IV crush warning and `[24.10]`'s event-driven caution describe.
- Could you explain, in your own words, why combining multiple Greeks' effects is necessary for a complete picture (`[22.07]`)?
- Would your estimates change if this were a SHORT position instead of long? Recalculate Q1 and Q4 for a short call/put to check your understanding.

---
*Educational content only. Not investment advice.*
