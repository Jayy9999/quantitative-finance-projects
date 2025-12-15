
# Monte Carlo Stock Price Simulation Using Geometric Brownian Motion

## Overview
This project implements a Monte Carlo simulation framework to model and forecast equity price paths using **Geometric Brownian Motion (GBM)**. The model is applied to historical equity price data to estimate future price distributions and risk characteristics.

## Methodology
- Modeled stock prices using the GBM stochastic differential equation:
  
  dS = μS dt + σS dW

- Estimated drift (μ) and volatility (σ) from historical log returns
- Simulated multiple price paths over a fixed time horizon
- Generated empirical distributions of terminal prices
- Computed expected return, volatility, and confidence intervals

## Application
- Applied the model to **NVIDIA (NVDA)** historical price data
- Visualized simulated price paths and terminal value distribution
- Assessed downside risk and dispersion across scenarios

## Tools & Technologies
- Python
- NumPy
- Pandas
- Matplotlib

## Key Learning Outcomes
- Practical implementation of stochastic processes in finance
- Monte Carlo simulation for risk and return estimation
- Translation of continuous-time finance models into numerical simulations

## Files
- `Monte_Carlo_Stock_Price_Simulation.ipynb` — Python notebook containing data processing, simulation logic, and visualizations

