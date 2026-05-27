# Equity Backtesting Engine

Backtesting engine testing momentum and mean reversion trading strategies across 20 S&P 500 stocks.

## Strategies

**Momentum** — buys the top 5 stocks by 12-month return each month. Based on Jegadeesh and Titman (1993).

**Mean Reversion** — buys the 5 most oversold stocks each month using z-score analysis.

**Combined** — equal-weighted portfolio of both strategies to reduce volatility.

## Testing Period Results (2023-2024)

| Strategy | Annualized Return | Sharpe Ratio | Max Drawdown |
|----------|------------------|--------------|--------------|
| Momentum | 40.90% | 2.47 | -3.68% |
| Mean Reversion | 18.69% | 1.42 | -4.16% |
| Combined | 29.79% | 2.36 | -3.39% |
| SPY Benchmark | 19.79% | 1.81 | -4.03% |

All three strategies outperformed SPY on both return and risk-adjusted basis on data never seen during development.

## Training Period Results (2018-2022)

| Strategy | Annualized Return | Sharpe Ratio | Max Drawdown |
|----------|------------------|--------------|--------------|
| Momentum | 23.22% | 0.96 | -20.18% |
| Mean Reversion | 21.03% | 0.77 | -29.06% |
| Combined | 20.60% | 0.86 | -21.95% |
| SPY Benchmark | 13.30% | 0.65 | -33.72% |

## Built With

Python, Pandas, NumPy, Matplotlib, yfinance

## Author

Yuv Hingarh | NYU Economics & Data Science
