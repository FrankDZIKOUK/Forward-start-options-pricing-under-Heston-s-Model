# Forward-Start Options Pricing and Hedging under the Heston Model

## Overview

This project focuses on the pricing and hedging of **forward-start options** within the **Heston stochastic volatility model**. The main objective is to derive analytical pricing and hedging formulas using Fourier transform techniques and characteristic functions, and to validate them numerically through Monte Carlo simulations.

In particular, the project compares the **Ivi simulation scheme** with the **Quadratic Exponential (QE) scheme** for forward-start options. While such a comparison has already been extensively studied in the case of **vanilla options** (see Eduardo Abi Jaber. *Simulation of square-root processes made simple: applications to the Heston model*. École Polytechnique, CMAP, June 2025.), this work extends the analysis to **path-dependent forward-start derivatives**, which are more challenging.

## Objectives

The main goals of the project are:

- Derive a **closed-form expression** for the price of forward-start options at any time under the Heston model using **Fourier transform techniques** and **characteristic functions**.
- Obtain **explicit analytical expressions** for hedging strategies within a **quadratic hedging framework**.
- Assess the **performance** of the Ivi and Quadratic Exponential (QE) discretization schemes when applied to forward-start options.
- Implement **Monte Carlo simulations** for pricing and hedging in Python.

## Methodology

- **Modeling**: Heston stochastic volatility model
- **Analytical tools**: Stochastic calculus, characteristic functions, Fourier methods
- **Numerical methods**: Monte Carlo simulation, Ivi and Quadratic Exponential (QE) schemes
- **Hedging framework**: Quadratic hedging
- **Implementation**: Python (NumPy, SciPy, Matplotlib)

## Key Results

- Derived a **closed-form pricing formula** for forward-start options under the Heston model.
- Obtained **analytical expressions for optimal hedging strategies** in a quadratic hedging framework.
- Validated theoretical prices through Python-based Monte Carlo simulations.
- Compared the **Ivi and QE schemes**

