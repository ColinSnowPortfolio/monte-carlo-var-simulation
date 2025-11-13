# Monte Carlo Value at Risk (VaR) Simulation

This project models portfolio risk using Monte Carlo simulations to estimate Value at Risk (VaR) and Conditional VaR (CVaR). The goal is to demonstrate quantitative finance techniques using Python and applied mathematics.

## Overview

This simulation:
- Generates correlated asset returns using a multivariate normal distribution.
- Simulates thousands of portfolio outcomes to estimate risk.
- Calculates 95% and 99% Value at Risk (VaR) and Conditional VaR (expected shortfall).
- Visualizes the loss distribution and tail risk.

## Mathematical Background

Value at Risk (VaR) is the loss threshold such that:
\[
P(Loss > VaR_\alpha) = 1 - \alpha
\]
For a confidence level α (e.g., 0.95 or 0.99), VaR gives the smallest loss expected at most α% of the time.

Conditional VaR (CVaR) measures the **expected loss beyond VaR**:
\[
CVaR_\alpha = E[Loss | Loss > VaR_\alpha]
\]

These are standard tools in quantitative risk management and portfolio optimization.

## Tools and Libraries

- Python 3.11
- NumPy
- Pandas
- Matplotlib / Seaborn
- JupyterLab

## Example Output

- Simulated loss distribution
- Calculated VaR/CVaR at multiple confidence levels
- Comparison with analytical normal approximation

## Future Extensions

- Implement Historical and Parametric VaR.
- Compare Python and C++ performance.
- Introduce non-normal returns (e.g., t-distribution or GARCH models).

## Next Steps

This is a part of a portfolio exploring data analysis, quantitative modeling, and financial mathematics.

*Created by Colin Snow, Mathematics Undergraduate (Year 2)*  
*Focus: Quantitative Finance, Applied Math, Data Analysis*
*Independent Project*
