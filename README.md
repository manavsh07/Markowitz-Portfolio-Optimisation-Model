# Markowitz-Portfolio-Optimisation-Model
GMV & Mean-Variance Optimized Portfolio Model
AFIN8039 Portfolio Management - Individual Assignment

Project Overview

This project applies Markowitz’s Mean-Variance Portfolio Optimization to construct and analyze different portfolios for the equity investment team at AFIN Super, an Australian superannuation fund. The analysis focuses on constructing Global Minimum Variance (GMV) Portfolios and Optimal Portfolios with and without short sales, evaluating their performance across training and testing periods.

Objective

Implement Markowitz’s Portfolio Optimization to construct risk-efficient portfolios.
Compare Global Minimum Variance (GMV) Portfolios and Optimal Portfolios under different constraints.
Test portfolio performance across different market conditions.
Identify practical challenges in portfolio construction.

Methodologies Used
1. Portfolio Construction:
Global Minimum Variance (GMV) Portfolio
Portfolio that minimizes risk (variance) without considering returns.
Mean-Variance Optimized Portfolio (OPT)
Portfolio that maximizes the Sharpe ratio based on risk-return tradeoff.
Constraints Applied:
Short Sales Allowed vs. No Short Sales
Portfolio weight allocations optimized using covariance matrices.

2. Performance Evaluation:
Training Period: 1 Jan 2020 - 31 Dec 2021 (Risk-free rate = 0.25% p.a.)
Testing Period: 1 Jan 2022 - 31 Dec 2022 (Risk-free rate = 2.00% p.a.)

Metrics Used:
Expected Return
Annualized Standard Deviation
Sharpe Ratio
Portfolio Weights Distribution
Key Findings & Insights
GMV portfolios minimize risk but may have suboptimal returns.
Optimal portfolios (MVO) achieve better risk-adjusted returns but are sensitive to input assumptions.

Impact of Short Sales:
Allowing short sales leads to more aggressive weight allocations and higher Sharpe ratios.
Restricting short sales results in more diversified portfolios.
Market Conditions Influence Performance:
Portfolios optimized in the training period may not perform as expected in the testing period due to market shifts.

Files in Repository:
GMV Portfolio Optimisation for 50 stocks.xls → Contains all calculations, portfolio weights, and risk-return analysis.
README.md → Overview of the project.

How to Use This Model:
Download the Excel file and explore different portfolio allocations.
Modify input stock data and adjust optimization constraints to observe changes.
Analyze the risk-return tradeoff for different portfolios using the provided results.
