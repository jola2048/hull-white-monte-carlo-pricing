# hull-white-monte-carlo-pricing
Pricing Interest Rate Caps and Floors via Monte Carlo simulation in the Hull-White model (Euler-Maruyama scheme) with parameter sensitivity analysis and corporate hedging case study.

# Hull-White Monte Carlo Pricing

Pricing Interest Rate Caps and Floors via Monte Carlo simulation in the single-factor Hull-White short-rate model, discretized with the Euler-Maruyama scheme.

## Features
* **Short-Rate Simulation:** Vectorized Euler-Maruyama discretization for the Ornstein-Uhlenbeck process under the risk-neutral measure $\mathbb{Q}$.
* **Derivative Valuation:** Monte Carlo pricing of caplets and floorlets with path-dependent stochastic discounting.
* **Sensitivity Analysis:** Visual analysis of how mean reversion speed ($a$) and volatility ($\sigma$) affect option premiums.
* **Hedging Case Study:** Cumulative premium estimation for a $100M portfolio over a 5-year horizon.

