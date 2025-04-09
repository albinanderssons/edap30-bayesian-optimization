# Bayesian Optimization Lab

This project demonstrates the implementation and application of Bayesian Optimization (BO) for hyperparameter optimization, using Gaussian Processes (GPs) as surrogate models. The lab provides both theoretical understanding and practical implementation of BO concepts.

## Overview

Bayesian Optimization is a powerful technique for optimizing black-box functions that are expensive to evaluate. It's particularly useful for hyperparameter optimization in machine learning models. The process involves:

1. Learning a model of the function (surrogate model)
2. Finding promising points to evaluate next
3. Evaluating the selected points
4. Refining the model using new observations

## Key Concepts

- **Surrogate Models**: The project uses Gaussian Processes (GPs) as surrogate models, which are among the most popular choices for BO
- **Uncertainty Estimation**: The surrogate models provide uncertainty estimates for predictions
- **Expected Improvement**: Used as an acquisition function to guide the optimization process