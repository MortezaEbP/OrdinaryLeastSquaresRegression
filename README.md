# OrdinaryLeastSquaresRegression
## Implementation of the Ordinary Least Squares (OLS) Regression algorithm in Python.

## Overview:

OLS Regression is a linear regression algorithm used to model the relationship between a dependent variable and one or more independent variables. It aims to find the best-fitting linear equation that minimizes the sum of squared differences between the observed and predicted values.

# Mathematical Formulation:

In the OLS algorithm, the goal is to find the coefficients (weights) and the intercept (bias) of the linear equation that best fits the data. The equation for the linear model can be expressed as:
$${\Huge\displaystyle \Huge \ y = X\beta + \epsilon }$$

## Where:
• y are the coefficients representing the influence of each input feature. 

• X are the coefficients representing the influence of each input feature.

• β the coefficients representing the influence of each input feature.

• ${\large \mathbf{\epsilon}}$ are the coefficients representing the influence of each input feature.




The coefficients ${\mathbf{\beta}}$ are calculated using the least squares method, which involves minimizing the sum of squared errors. The optimal coefficients can be computed as:

$${\Huge\displaystyle  \min_{\mathbf{\beta}, b} \sum_{i=1}^{n} (y_i - (\mathbf{\beta} \cdot \mathbf{x}_i + \beta_0))^2 }$$

$${\Huge\displaystyle \Huge \beta = (X^T X)^{-1} X^T y}$$

## Where:
${\mathbf{X^T}}$ is the transpose of the input feature matrix.
${\mathbf{(X^T X)^{-1}}}$ is the inverse of the matrix


### Vectorized Computations:

All calculations in this implementation are performed using vectorized operations, which take advantage of NumPy's efficient array operations. This enhances computational efficiency and simplifies the code.


#### Contributing:

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to open an issue or create a pull request.
