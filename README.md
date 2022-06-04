# ML-using-Linear-Regression
This code demonstrates the basics of machine learning by implementing algorithms for linear regression of multiple variables. Given a training set of data with any number of features, it can learn parameters that fit an optimal linear function to the data and make predictions.

Steps to implement linear regression using this code:
1. Obtain raw initial data from somewhere and put it into a csv file.
2. Modify the data by adding the x_0 feature. Also, feature normalize the data if necessary.
3. Choose a learning rate by plotting the speed of convergence of the error function with respect to the number of iterations.
4. Depending on the situation, apply a gradient descent algorithm to return the optimal parameters that minimizes the error function.
5. If there are only two features, plot linear regression using the optimal parameters.

Reference
- xj_i is the ith element of the jth training example
- Training examples range from x1 to xm
- Each training example has elements ranging from x_0 to x_n+1
- Use numpy 2d arrays as preferred data structure whenever possible
- If learning rates are too large, J can diverge and blow up, resulting in really large values the computer cannot comprehend
- Csv files MUST include headers (x_0, x_1, ..., y) or else the first training ex will be cut off

Data
- linreg1.csv - no feat norm, alpha = 0.01
- linreg2.csv - feat norm, alpha = 0.3
