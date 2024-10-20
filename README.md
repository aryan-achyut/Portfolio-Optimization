# Portfolio Optimization Using Heston Stochastic Volatility Model

## Project Overview

This project investigates the optimization of portfolio allocations for the top 20 companies in the S&P 500 using advanced financial modeling techniques. By employing the Heston Stochastic Volatility Model integrated with jump processes, we analyze the performance of portfolios across varying investment horizons (1, 3, 5, 10, and 20 years).

## Objectives

- To enhance risk-adjusted returns through sophisticated modeling techniques.
- To analyze the impact of different time horizons on portfolio performance metrics.
- To provide insights into effective risk management strategies.

## Techniques and Technologies Used

- **Heston Stochastic Volatility Model**: Captures changing volatility over time.
- **Jump Processes**: Accounts for sudden market movements that can impact investment returns.
- **Monte Carlo Simulations**: Evaluates portfolio metrics such as Average Sharpe Ratio, Maximum Drawdown, and Value at Risk (VaR).
- **Dynamic Portfolio Optimization**: Considers varying risk aversion levels for tailored investment strategies.

## Key Findings

- Longer investment horizons improve risk-adjusted returns, indicated by higher Sharpe Ratios and lower drawdowns.
- The incorporation of volatility dynamics enhances risk management and strategic asset allocation.

## Results Summary

| **Time Horizon** | **Average Sharpe Ratio** | **Average Maximum Drawdown** | **Average VaR 95%**       |
|------------------|--------------------------|-------------------------------|----------------------------|
| 1 Year           | 1.7364                   | -0.0061                       | 0.0484                     |
| 3 Years          | 2.0729                   | -0.0000546                    | 0.0539                     |
| 5 Years          | 4.4276                   | 0.0000                        | 0.0899                     |
| 10 Years         | 3.2689                   | -0.0165                       | 0.0482                     |

## Installation

To run this project, clone the repository and install the required packages:

```bash
git clone https://github.com/yourusername/portfolio-optimization.git
cd portfolio-optimization
pip install -r requirements.txt
