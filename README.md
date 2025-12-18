# Black–Scholes Pricing and Greeks for European Options

This project implements the Black–Scholes model for European call and put options,
along with closed-form Greeks and payoff visualizations, in Python.

## 1. Overview

- Implement analytic Black–Scholes pricing for European calls and puts.
- Compute key Greeks (Delta, Gamma, Vega, Theta, Rho).
- Visualize payoff diagrams and sensitivities.
- Walk through a realistic hedging example use case.

## 2. Methods

- Black–Scholes closed-form solution for European options.
- Analytic Greeks using $d_1$ and $d_2$.
- Payoff functions for long/short calls and puts.
- Parameter sweeps over underlying price and volatility.

## 3. Example use case

The notebook concludes with a worked example of a long at-the-money index call:

- Compute theoretical price and Greeks.
- Visualize payoff at expiry.
- Inspect Delta vs underlying and price vs volatility.

## 4. Repository Structure
- plots/: delta and payoff plots
- src/: main Jupyter notebook
- .gitignore
- README.md
- requirements.txt


