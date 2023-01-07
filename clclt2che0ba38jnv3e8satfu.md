# #36 Machine Learning & Data Science Challenge 36

# VIF(Variation Inflation Factor), Weight of Evidence & Information Value. Why and when to use it?

### Variation Inflation Factor:

* It provides an index that measures how much the variance (the square of the estimate's standard deviation) of an estimated regression coefficient is increased because of collinearity.
    
* VIF = 1 / (1-R-Square of j-th variable) where R2 of jth variable is the coefficient of determination of the model that includes all independent variables except the jth predictor.
    
* Where R-Square of the j-th variable is the multiple R2 for the regression of Xj on the other independent variables (a regression that does not involve the dependent variable Y).
    
* If VIF &gt; 5, then there is a problem with multicollinearity.
    

### Understanding VIF:

* If the variance inflation factor of a predictor variable is 5 this means that the variance for the coefficient of that predictor variable is 5 times as large as it would be if that predictor variable were uncorrelated with the other predictor variables.
    
* In other words, if the variance inflation factor of a predictor variable is 5 this means that the standard error for the coefficient of that predictor variable is 2.23 times (√5 = 2.23) as large as it would be if that predictor variable were uncorrelated with the other predictor variables.
    

#### Weight of evidence (WOE) and information value (IV) are simple, yet powerful techniques to perform variable transformation and selection.

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672824814738/b0abed99-4c9e-4d3c-b26f-c1cf08bde973.png align="center")

#### The formula to create WOE and IV is;

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672824932873/1a49064c-d06c-43d2-a6cd-2547bc5562b0.png align="center")

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672825005277/785b289a-c074-4a99-8cf0-d8dd1a6e555f.png align="center")

#### Here is a simple table that shows how to calculate these values.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672825094796/d4d9c2e6-194e-4a54-9057-6b8042e9422b.png align="center")

#### The IV value can be used to select variables quickly.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672824861842/64d13674-b54a-4c7b-b47d-a62716355532.png align="center")