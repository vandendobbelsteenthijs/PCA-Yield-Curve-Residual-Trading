# PCA-Yield-Curve-Residual-Trading
PCA Yield Curve Residual Trading

Principal Component Residual Trading on the U.S. Treasury Curve
 Built end-to-end Python pipeline for a fixed-income mean reversion strategy: rolling 5-year PCA on U.S. Treasury yields
(2006–2026), residual signal generation via 20-day z-score, PC-neutral hedge construction.
Solved a 3×3 linear system per active trade to build level/slope/curvature-neutral hedges from three neighboring
tenors.
Ran 2016-2026 backtest across five transaction cost scenarios and identified breakeven at ≈0.15bp per leg..
Concluded that gross alpha exists (modified Sharpe 2.0) but is non-capturable for retail execution, a finding consistent
with efficiency of the market.
