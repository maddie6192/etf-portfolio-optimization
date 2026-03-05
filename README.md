# ETF Portfolio Optimization Using Risk-Return Models

## Overview
This project develops a data-driven framework for constructing ETF portfolios using optimization techniques rather than traditional rule-based allocation methods.

Using historical ETF data across equities, bonds, commodities, and international markets, multiple portfolio optimization models were implemented and compared.

## Data
The dataset includes 3 years of historical monthly returns for 8 ETFs representing diversified asset classes:
- SPY (S&P 500)
- QQQ (Nasdaq 100)
- IWM (Russell 2000)
- TLT (Long-term Treasury bonds)
- SHY (Short-term Treasury bonds)
- GLD (Gold ETF)
- VXUS (International equities)
- EFA (Developed international equities)

## Methods
The project evaluates five optimization approaches:

- Return maximization with a risk constraint
- Risk minimization with a return constraint
- Mean-variance portfolio optimization
- Minimum variance portfolio using covariance matrix
- Scenario-based robust optimization to improve worst-case performance

## Results
The analysis demonstrates how portfolio allocations change depending on investment objectives and risk tolerance.

Return-focused models favored higher-growth ETFs (SPY, QQQ), while risk-minimizing models shifted toward stable assets such as SHY and GLD.

A blended portfolio was recommended for moderate-risk investors:
- 40% SHY
- 31% GLD
- 15% SPY
- 14% QQQ

## Tools
- Excel
- Portfolio Optimization
- Quantitative Analysis
