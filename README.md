# High-Accuracy-Forward-Difference-Derivative-Using-Taylor-Series
## Project Overview
In this project, I implement a fourth-order accurate forward finite difference method to approximate derivatives of functions. Using the Taylor series expansion and extrapolation, I combine derivative approximations at different step sizes to eliminate the leading error term. I verify my results by computing the derivative of 
f(x) = x^6
and plotting the absolute error against the square of the step size to observe convergence.

## Features
* I compute derivatives using a forward finite difference formula.
* I created a Derivative Calculator class that allows flexible step sizes and functions.
* I visualize the absolute error vs. step size squared using matplotlib.
* I can easily modify the code for other functions or different step sizes.

## How I Use It
* I import the ForwardDerivative class from derivative_calculator.py.
* I define the function I want to differentiate.
* I create a derivative calculator with my function and a chosen initial step size.
* I call the derivative method to compute the derivative at any point.
*I adjust the step size and recompute to observe how the error changes.
*I plot the results with matplotlib to check convergence visually.

## Dependencies
* Python 3.x
* NumPy
* Matplotlib
