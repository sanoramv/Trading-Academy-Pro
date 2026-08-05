# CheatSheet 9 — Algorithmic & Quantitative Trading

> Covers Modules 29-30. Part of Module 35.

## Backtesting Pitfalls Checklist (`[29.03]`)
1. Look-ahead bias — using info not actually available at trade time
2. Survivorship bias — excluding delisted/failed instruments
3. Realistic transaction costs — spread, brokerage, slippage
4. Out-of-sample testing — data never used during development

## Overfitting Warning Signs (`[29.04]`)
- Too many parameters relative to data
- Suspiciously specific parameter values
- Large gap between in-sample and out-of-sample performance
- Implausibly smooth backtest equity curve

## Execution Algorithms (`[29.05]`)
| Algorithm | Behavior |
|---|---|
| TWAP | Splits order evenly across TIME |
| VWAP | Splits order to match typical VOLUME pattern |
| Iceberg | Displays only a small portion of the total order |

## Simple Bot Architecture (`[29.06]`)
```
[Data Feed] -> [Strategy/Signal] -> [RISK GATE, independent] ->
[Execution] -> [Logging/Monitoring]
```

## Statistical Foundations (`[30.02]`)
```
Mean = average
Variance = avg squared deviation from mean
Std Dev = sqrt(Variance)  [= "volatility"]
Skewness = asymmetry of distribution
Kurtosis = tail fatness (normal = 3; >3 = fat tails)
```

## Correlation vs. Cointegration (`[30.03]`)
```
CORRELATION:   co-movement of RETURNS
COINTEGRATION: stable, mean-reverting relationship between PRICE LEVELS
               (the stronger property PAIRS TRADING requires)
```

## Autocorrelation by Timescale (`[30.04]`, documented tendency)
```
Short-term (days)   -> often NEGATIVE (mean reversion)
Medium-term (months)-> often POSITIVE (momentum)
Long-term (years)   -> often NEGATIVE again (reversion)
```

## Kelly Criterion (`[26.04]`, `[30.01]`)
```
Kelly % = W - [(1-W)/R]   -- use a FRACTION in practice
```

---
*Educational content only. Not investment advice.*
