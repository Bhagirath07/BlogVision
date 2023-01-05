# #28 Machine Learning & Data Science Challenge 28

# How do you treat heteroscedasticity in regression?

* **Heteroscedasticity means unequal scattered distribution.**
    
* In regression analysis, we generally talk about heteroscedasticity in the context of the error term.
    
* Heteroscedasticity is **the systematic change in the spread of the residuals or errors over the range of measured values.**
    
* Heteroscedasticity is the problem because **Ordinary least squares (OLS)** regression assumes that all residuals are drawn from a random population that has a constant variance.
    

### What causes Heteroscedasticity?

* Heteroscedasticity occurs more often in datasets, where we have a large range between the largest and the smallest observed values.
    
* There are many reasons why heteroscedasticity can exist, and a generic explanation is that the error variance changes proportionally with a factor.
    

### **We can categorize Heteroscedasticity into two general types:**

### Pure Heteroscedasticity:-

* It refers to cases where we specify the correct model and let us observe the non-constant variance in residual plots.
    

### Impure Heteroscedasticity:-

* It refers to cases where you incorrectly specify the model, and that causes the non-constant variance.
    
* When you leave an important variable out of a model, the omitted effect is absorbed into the error term.
    
* If the effect of the omitted variable varies throughout the observed range of data, it can produce telltale signs of heteroscedasticity in the residual plots.
    

## How to Fix Heteroscedasticity?

### Redefining the variables:

* If your model is a cross-sectional model that includes large differences between the sizes of the observations, you can find different ways to specify the model that reduces the impact of the size differential.
    
* To do this, change the model from using the raw measure to using rates and per capita values.
    
* Of course, this type of model answers a slightly different kind of question. You’ll need to determine whether this approach is suitable for both your data and what you need to learn.
    

### Weighted regression:

* It is a method that assigns each data point a weight based on the variance of its fitted value.
    
* The idea is to give small weights to observations associated with higher variances to shrink their squared residuals.
    
* Weighted regression minimizes the sum of the weighted squared residuals. When you use the correct weights, heteroscedasticity is replaced by homoscedasticity.