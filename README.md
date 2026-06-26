# Function-Approximation-Comparison

Comparison of polynomial regression and neural networks for function approximation across smooth, oscillatory, and piecewise functions.

## Overview
This project explores how model design choices affect function approximation performance using polynomial regression and neural networks across different function types.

Experiments analyze the effects of:
- Polynomial degree
- Neural network architecture
- Activation functions

Performance is evaluated using Mean Squared Error (MSE).

---

## Functions Tested
- Smooth: y = x²
- Oscillatory: y = sin(5x)
- Piecewise: y = |x|

---

## Libraries Used
- NumPy
- Matplotlib
- scikit-learn
- PyTorch

---

## Key Findings
- Low-degree polynomials underfit complex functions
- Neural networks improve with increased capacity up to a point
- Tanh performed better on oscillatory functions
- Model performance depends strongly on function structure

---

## Topics
Machine Learning, Neural Networks, Polynomial Regression, Function Approximation, PyTorch




[View Slides](https://github.com/carterglover20/Function-Approximation-Comparison/raw/main/Function_Approximation_Slides.pdf)
