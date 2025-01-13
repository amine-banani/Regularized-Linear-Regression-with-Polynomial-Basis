# Regularized Linear Regression with Polynomial Basis

This project implements a program for regularized linear regression using a polynomial basis. The program supports three methods for optimization: **Closed-Form Least Squares Estimation (LSE)**, **Steepest Descent**, and **Newton's Method**. The focus is on implementing these techniques from scratch with minimal reliance on external libraries.

---

## Features

1. **Optimization Methods**:
   - **Closed-Form LSE**: Analytical solution for regularized regression.
   - **Steepest Descent**: Iterative optimization to minimize the cost function.
   - **Newton's Method**: Optimization using second-order derivatives for faster convergence.

2. **Polynomial Basis Transformation**:
   - Converts input data into a polynomial feature space for regression.
   - Customizable degree of the polynomial.

3. **Regularization**:
   - Includes regularization to prevent overfitting (Ridge Regression).

4. **Visualization**:
   - Plots data points, regression curves, and the effects of regularization.
   - Visualizes convergence of optimization methods.

---

## Implementation Highlights

- All functions for matrix operations, gradient computation, and Hessian calculation were implemented manually.
- Little to no external libraries (e.g., NumPy, SciPy) were used for core computations.

