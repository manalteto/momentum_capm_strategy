# Momentum Strategy and CAPM Alpha Analysis

This project implements a momentum-based long-short equity strategy using U.S. stocks, starting in 1980. The strategy involves sorting stocks into deciles based on 12-month returns and volatility, and then forming long and short portfolios to test for persistent return anomalies.

## Objectives
1. Construct momentum decile portfolios based on past 12-month returns.
2. Compute CAPM alphas and betas for the winner (D10), loser (D1), and D10–D1 spread portfolios.
3. Combine return and volatility ranks to form a DD score and evaluate a long-short DD-based strategy.
4. Compare CAPM performance between simple momentum and DD-enhanced strategies.

## Tools & Data
- Python (pandas, numpy, matplotlib, statsmodels)
- WRDS / CRSP or Yahoo Finance for stock returns
- Kenneth French Data Library for market and risk-free rate data

## Outputs
- Return time series of constructed portfolios
- CAPM regression tables with alpha, beta, and t-statistics
- Strategy performance plots

## Insight
Evaluates whether incorporating volatility improves momentum-based excess returns, and whether the strategy consistently produces positive alphas that challenge the efficient market hypothesis.
