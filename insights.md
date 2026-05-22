# Key Findings & Business Insights

## Sector-Level Analysis

### Returns (365-Day)
- Metals and Energy sectors led annual returns, driven by 
  commodity supercycles
- IT sector showed consistent momentum with lower volatility
- FMCG showed defensive characteristics — low 30d drawdown 
  during market correction

### Liquidity
- Banking sector dominates total market turnover, indicating 
  high institutional participation
- Metals show high volume spikes suggesting event-driven trading

## Stock-Level Insights

### Top Momentum Stocks
- Stocks in the top-right quadrant of the scatter plot (high momentum 
  + high 52w position) represent strong trending candidates
- Stocks in bottom-right (high momentum + low 52w position) may 
  represent recovery plays

## Data Quality Notes
- Several large-cap stocks had comma-formatted numeric fields 
  requiring custom cleaning logic
- 2 stocks had null sector mapping and were excluded from 
  sector-level aggregations
- Momentum score weighted 60% annual / 40% monthly return to 
  reduce short-term noise

## Limitations & Next Steps
- Dataset is a single-day snapshot — adding time-series data would 
  enable beta computation and proper risk-adjusted analysis
- P/E ratios and EPS were manually sourced — automating via 
  financial API (e.g. NSE API) would improve scalability
- Future: add Nifty 50 index as benchmark for relative performance
