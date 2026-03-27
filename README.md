# Bias- Variance Tradeoff using Monte Carlo Simulation
## Overview 
This project demontrates the bias-variance tradeoff using polynomial regression models. Through simulation, we analyze how model complexity affects prediction error.
## Objective 
- Understand the concept of bias and variance
- Study the effect of model complexity
- Demonstrate underfitting and overfitting
## Theoretical Background
Prediction error can be decomposed as:
Error = Bias^2 + Variance + Irreducible Error
- Bias: Error due to overly simple models
- Variance: Error due to sensitivity to data
- Tradeoff: Increasing complexity reduces bias but increases variance
## Methodology
- True function:
  y = x^2 + ε, where ε ~ N(0,1)
- Steps:
  1. Generates synthetic data
  2. Fit polynomial models of different degrees
  3. Run multiple simulations
  4. Compute:
    - Bias^2
    - Variance
  5.Visualize results
## Results 
- Low-degree models : High bias, Low variance(Underfitting)
- High-degree models : Low bias, High variance(Overfitting)
- Optimal model balances both
## Tools Used
- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

