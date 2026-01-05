#  Optimal Delta Hedging Techniques

**Stochastic Simulation – UvA & VU Amsterdam**

This repository contains the code and report for a group assignment developed for the *Stochastic Simulation* course at the University of Amsterdam (UvA) and Vrije Universiteit Amsterdam (VU). The project studies option pricing and delta hedging within and beyond the classical Black–Scholes framework, combining analytical results with Monte Carlo simulation and stochastic modeling.

---
## Project Overview

The project consists of four main components:

### 1. Black–Scholes Pricing and Monte Carlo Simulation

* Derived and implemented the Black–Scholes model under risk-neutral pricing.
* Calibrated volatility using S&P 500 (SPY) daily data.
* Compared analytic option prices with Monte Carlo estimates and confidence intervals.

### 2. Variance Reduction via Antithetic Sampling

* Implemented antithetic variates for Monte Carlo pricing.
* Compared estimator variances using an F-test to assess statistical significance.

### 3. Delta Hedging with and without Execution Delays

* Simulated discrete-time delta hedging strategies under GBM dynamics.
* Modeled execution delays using an M/M/1 queue.
* Analyzed the distribution of hedging errors and the impact of trading frictions.

### 4. Model Risk: Jumps and Regime-Switching Volatility

* Simulated stock prices using a Lévy jump–diffusion model.
* Implemented a Markov-switching volatility model with low- and high-volatility regimes.
* Evaluated pricing errors and hedging performance under the different model specifications.

---

## Repository Structure

* [Report – Theoretical Background & Results](./assignment3_theory.pdf)
* `assignment3_deltahedging` – Numerical implementations and simulation notebook

---

## Key Topics and Tools

* Black–Scholes option pricing
* Monte Carlo simulation
* Variance reduction techniques
* Delta hedging
* Queueing theory (M/M/1)
* Lévy jump–diffusion processes
* Markov-switching volatility models

---
## Authors

**Probability Pirates**
* Anna De Martin
* Zheng Xia 
* Boris Merkies
