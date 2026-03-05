# ETF Portfolio Optimization Using Risk-Return Models

## Overview
This project explores data-driven portfolio construction using optimization techniques instead of traditional rule-based allocations such as the 60/40 portfolio.

Using historical ETF return data, multiple optimization approaches were developed to evaluate how portfolio allocations change under different investment objectives.

## Data
The dataset includes 3 years of monthly return data for 8 ETFs representing major asset classes:

- SPY – S&P 500
- QQQ – Nasdaq 100
- IWM – Russell 2000
- TLT – Long-term Treasury bonds
- SHY – Short-term Treasury bonds
- GLD – Gold ETF
- VXUS – International equities
- EFA – Developed international markets

These ETFs provide exposure to equities, fixed income, commodities, and international markets.

## Optimization Models
Five portfolio strategies were evaluated:

1. Maximize expected return with a risk constraint
2. Minimize risk with a return requirement
3. Mean-variance optimization
4. Minimum variance portfolio using covariance matrix
5. Scenario-based optimization to improve worst-case monthly performance

## Key Findings
Different objectives produce significantly different portfolio allocations:

- Return-focused models allocate more heavily to SPY and QQQ
- Risk-minimizing models shift toward stable assets like SHY and GLD
- Scenario-based optimization improves worst-case performance

Recommended moderate-risk allocation:

- 40% SHY
- 31% GLD
- 15% SPY
- 14% QQQ

## My Contributions
- Implemented portfolio optimization models
- Analyzed risk-return tradeoffs across investment strategies
- Interpreted results and recommended a balanced ETF allocation

## Tools
- Excel
- Optimization modeling
- Quantitative analysis


## My Contributions

This project was completed as part of the MS Business Analytics program at Arizona State University.

My contributions included:
- analyzing ETF return data
- evaluating portfolio optimization strategies
- interpreting risk-return tradeoffs
- recommending a balanced portfolio allocation
