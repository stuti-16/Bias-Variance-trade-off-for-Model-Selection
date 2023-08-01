Here we assume an arbitrary function 𝑓(𝑥) and compute its value on 10,000 equally-spaced data points. We try to find out the optimal complexity of the regression model that can best estimate this function.

Steps to follow:

- Take a trigonometric function and a choose an error function (N(0, sigma-sq)). Generate  data  set of 10,000 instances. Fit polynomials of order 1 - 10 and estimate and plot total error, Bias, Variance,   

- training and validation error for each  using 10-fold cross validation.   Create the folds using Python function and compute all errors using the equations given in textbook.  Select the optimal model.

- For the selected model, estimate and plot total error, Bias, Variance,    training and validation error for training set sizes  1K, 2K, ... 10K. Use 10-fold cross validation for each training set, and the functions coded earlier for estimating the error.
