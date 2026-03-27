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
  <img width="684" height="448" alt="Generated data" src="https://github.com/user-attachments/assets/7677dd70-a91a-4593-98c8-c47167b9e405" />
  <img width="620" height="440" alt="Model complexity comparison" src="https://github.com/user-attachments/assets/80ab3b23-2001-4bd5-8ed7-50c235883ff5" />
  <img width="718" height="462" alt="Bias-Variance Tradeoff" src="https://github.com/user-attachments/assets/35ee901e-ce66-4dc7-9186-b5fe171bcd8c" />
 
## Results 
- Low-degree models : High bias, Low variance(Underfitting)
- High-degree models : Low bias, High variance(Overfitting)
- Optimal model balances both
- The simulation confirm that bias decreases and variance increases with model complexity.
- The minimum total error occurs at an intermediate model complexity.
## Tools Used
- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

