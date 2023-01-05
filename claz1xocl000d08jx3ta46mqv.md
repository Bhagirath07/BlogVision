# #6 Machine Learning & Data Science Challenge 6

# What is R square? [were to use and were not]

- #### R-squared is a statistical measure of how close the data are to the fitted regression line. It is also known as the coefficient of determination, or the coefficient of multiple determination for multiple regression.

- The definition of R-squared is **the percentage of the response variable variation that is explained by a linear model.**

> - **R-squared = Explained variation / Total variation**
- **R-squared** is always between **0** and **100%**.
- **0%** indicates that **the model explains none of the variability of the response data around its mean.**
- **100%** indicates that **the model explains all the variability of the response data around its mean.**

- In general, the higher the R-squared, the better the model fits your data.


> ![01.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669534342606/ZP_5Lb_KS.png align="left")

- There is a problem with the R-Square. The problem arises when we ask this question to ourselves.** Is it good to help as many independent variables as possible?**

- The answer is No because we understood that each independent variable should have a meaningful impact. But, even** if we add independent variables which are not meaningful**, will it improve the R-Square value?

- Yes, this is the basic problem with R-Square. How many junk independent variables or important 
independent variables or impactful independent variables you add to your model, the R-Squared value will always increase. 

- It will never decrease with the addition of a newly independent variable, whether it could be an impactful, non-impactful, or bad variable, so we need another way to measure equivalent R-Square, which penalizes our model with any junk independent variable.

- So, we calculate the **Adjusted R-Square** with a better adjustment in the formula of the generic R-square.

> ![02.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1669534547627/EWaYH5Qqu.png align="left")
