# Linear Regression from Scratch

A comprehensive implementation of linear regression using three different optimization algorithms, built from scratch in Python and validated against scikit-learn.

## Features

- **Three Optimization Algorithms:**
  - Batch Gradient Descent (smooth, predictable convergence)
  - Stochastic Gradient Descent (fast convergence with mini-batches)
  - Analytical Solution (exact solution using normal equation)

- **Implementation:**
  - Scikit-learn similar API
  - Comprehensive testing and validation
  - Mathematical explanation and regularization
  - Detailed performance analysis

## Key Results

All implementations achieve ~0.575 R² on California Housing dataset:
- **Analytical**: Exact solution in 0.037s
- **SGD**: Fast convergence (28 epochs, 0.265s)  
- **Batch GD**: Smooth convergence (308 epochs, 0.602s)
- **Sklearn**: Baseline comparison (0.575 R², 0.048s)

## What's Inside

- **Mathematical foundations** with clear explanations
- **Three solver implementations** from scratch
- **Convergence analysis** and algorithm trade-offs
- **Comprehensive visualizations** (loss curves, coefficient comparisons)
- **Sklearn validation** against LinearRegression()
