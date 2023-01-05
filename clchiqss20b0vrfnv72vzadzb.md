# #29 Machine Learning & Data Science Challenge 29

# What is multicollinearity, and how do you treat it?

## Multicollinearity:

* **It means independent variables are highly correlated to each other. In regression analysis, it's an important assumption that the regression model should not be faced with a problem of multicollinearity.**
    
* If two explanatory variables are highly correlated, it's hard to tell, which affects the dependent variable.
    
* Let's say Y is regressed against X1 and X2 and where X1 and X2 are highly correlated.
    
* Then the effect of X1 on Y is hard to distinguish from the effect of X2 on Y because any increase in X1 tends to be associated with an increase in X2.
    
* Another way to look at the multicollinearity problem is: Individual t-test P values can be misleading.
    
* It means a P-value can be high, which means the variable is not important, even though the variable is important.
    

### Correcting Multicollinearity:

1. Remove one of the highly correlated independent variables from the model. If you have two or more factors with a high VIF, remove one from the model.
    
2. Principle Component Analysis (PCA) - It cut the number of interdependent variables to a smaller set of uncorrelated components. Instead of using highly correlated variables, use components in the model that have an eigenvalue greater than 1.
    
3. Run PROC VARCLUS and choose the variable that has a minimum (1-R2) ratio within a cluster.
    
4. Ridge Regression - It is a technique for analyzing multiple regression data that suffer from multicollinearity.
    
5. If you include an interaction term (the product of two independent variables), you can also reduce multicollinearity by "centering" the variables. By "centering," it means subtracting the mean from the values of the independent variable before creating the products.
    

### When is multicollinearity not a problem?

1. If your goal is to predict Y from a set of X variables, then multicollinearity is not a problem. The predictions will still be accurate, and the overall R2 (or adjusted R2) quantifies how well the model predicts the Y values.
    
2. Multiple dummy (binary) variables that represent a categorical variable with three or more categories.