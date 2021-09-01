# Polynomial Regression:
Polynomial Regression is a regression algorithm that models the relationship between a dependent(y) and independent variable(x) as nth degree polynomial. 
The Polynomial Regression equation
y= b0+b1x1+ b2x12+ b2x13+...... bnx1n
It is also called the special case of Multiple Linear Regression in ML. Because we add some polynomial terms to the Multiple Linear regression equation to convert it into Polynomial Regression.
It is a linear model with some modification in order to increase the accuracy.
The dataset used in Polynomial regression for training is of non-linear nature.
It makes use of a linear regression model to fit the complicated and non-linear functions and datasets.
Hence, "In Polynomial regression, the original features are converted into Polynomial features of required degree (2,3,..,n) and then modeled using a linear model."

# Need for Polynomial Regression:
If we apply a linear model on a linear dataset, then it provides us a good result as we have seen in Simple Linear Regression, but if we apply the same model without any modification on a non-linear dataset, then it will produce a drastic output. Due to which loss function will increase, the error rate will be high, and accuracy will be decreased.
So for such cases, where data points are arranged in a non-linear fashion, we need the Polynomial Regression model. We can understand it in a better way using the below comparison diagram of the linear dataset and non-linear dataset.


