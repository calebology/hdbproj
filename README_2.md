# Mistakes Made
## Regression Model Performance with statsmodel library
I forgot to add a constant to all the tabulations before producing the statsmodel regression output. This resulted in the lack of a constant/intercept value in the regression output involving statsmodel.

This can be resolved by adding the following lines of code before producing the individual simple regression output.

X = sm.add_constant(X)
sm.OLS(y,X)

## Checking explanatory variables
I opted to individually cross check different explanatory variables against the dependent variable of housing prices per square meter. The goal was to find the most suitable explanatory variables that could be included in the multiple regression model without having the adjusted R squared score taking a significant penalty.

There must be a more efficient method that I have not tried instead of applying brute force with this method. Perhaps iteration would be the right way to approach this, but I am unsure.