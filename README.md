# Monte-Carlo-Risk-Analytics-and-Option-Pricing

## Overview

This project implements and compares multiple Monte Carlo simulation techniques for derivative pricing and market risk measurement under the Black-Scholes framework.

The study evaluates Euler-Maruyama, Milstein, and Exact Log-Normal simulation methods for European option pricing, benchmarked against the analytical Black-Scholes solution. The framework is then extended to practical risk management applications including Value at Risk (VaR), Expected Shortfall (ES), sensitivity analysis, and scenario-based stress testing.

The project demonstrates how Monte Carlo methods can be applied beyond pricing to support risk quantification and regulatory risk analytics.

## Key Features

* Implemented Euler-Maruyama, Milstein, and Exact simulation schemes for Geometric Brownian Motion (GBM)
* Benchmarked Monte Carlo prices against the Black-Scholes analytical solution
* Performed convergence analysis across different simulation path counts
* Analysed parameter sensitivities including volatility and strike price effects
* Estimated Value at Risk (VaR) and Expected Shortfall (ES)
* Conducted scenario-based stress testing under adverse market conditions
* Visualised price distributions, convergence behaviour, and tail-risk characteristics

## Technologies

* Python
* NumPy
* SciPy
* Pandas
* Matplotlib
* Jupyter Notebook

## Key Findings

* Exact simulation provides the highest pricing accuracy when the analytical distribution is available.
* Monte Carlo estimates converge toward the Black-Scholes benchmark as the number of simulation paths increases.
* Expected Shortfall (ES) captures tail risk more effectively than VaR, supporting the rationale behind modern regulatory frameworks such as FRTB.
* Stress testing highlights the significant impact of volatility shocks and adverse market scenarios on derivative valuations.

## Applications

This framework can be extended to:

* Portfolio risk measurement
* Market risk analytics
* Stress testing and scenario analysis
* Regulatory capital modelling
* Exotic derivative pricing
* Advanced stochastic volatility models (e.g., Heston, SABR)

## Repository Structure

```text
├── Monte_Carlo_Risk_Analytics_and_Option_Pricing.ipynb
├── README.md

```

## Author

Yanhong Lu

Risk Analytics | Quantitative Finance | Python
