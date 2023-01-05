# #3 Machine Learning & Data Science Challenge 3

# OLS Stats Model (Ordinary Least Square)

- OLS is a **stats model**, which will help us in **identifying the more significant features that can have an 
influence on the output.** 

- OLS model in python is executed as:

 - **lm** = **smf.ols(formula = 'Sales ~ am+constant', data = data).fit() lm.conf_int() lm.summary()**


![1-06.jpg](https://cdn.hashnode.com/res/hashnode/image/upload/v1663936306145/FsSZiFMcD.jpg align="left")

- The higher the t-value for the feature, the more significant the feature is to the output variable. 

- The p-value plays a role in rejecting the Null hypothesis(The null hypothesis states the features has zero 
significance on the target variable.).

- If the p-value is less than 0.05(95% confidence interval) for a feature, then we can consider the feature to be significant.