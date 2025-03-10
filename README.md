﻿# Linear-Regression-From-Scratch

![image](https://github.com/user-attachments/assets/f340e943-3376-4dc0-98d6-d2f45b5eb9ce)

This project implements a basic linear regression model from scratch to refresh core machine learning and linear algebra concepts.

# Key Concepts
Data Types & Preprocessing:

Data is expected to be clean (no null values) and uniformly formatted.
We use Pandas for data manipulation and then convert data into NumPy arrays for efficient linear algebra operations.
# Matrix Operations:

In NumPy, arrays are treated as matrices.
This allows us to perform dot products for predictions and other linear algebra operations required by the algorithm.
Model Implementation:

 
# Gradient Descent:
![image](https://github.com/user-attachments/assets/2b3dd188-ffdf-4df6-b65a-53943e548741)


 
Two main steps in the training loop:
Loss Function Evaluation: Compute the MSE and its derivative with respect to each weight.
Weights Update: Update the weights using the calculated gradient (with a transpose operation where needed).

![image](https://github.com/user-attachments/assets/480617bf-178a-4571-8aec-2192f0e8af53)

## Convergence:

The training stops when the absolute change in loss falls below a defined tolerance or when the maximum number of iterations is reached.
