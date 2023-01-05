# #4 Machine Learning & Data Science Challenge 4

# What is L1 Regularization (L1 = lasso)?

- The main objective of creating a model(training data) is to ensure it properly fits the data and reduces the loss.

- Sometimes the model that is trained will fit the data but it may fail and give a poor performance during analyzing of data (test data). This leads to overfitting. Regularization came to overcome overfitting.

- Lasso Regression (**Least Absolute Shrinkage and Selection Operator**) adds “Absolute value of 
magnitude” of coefficient, as a penalty term to the loss function.

- Lasso shrinks the less important feature’s coefficient to zero; thus, removing some features altogether. So, this works well for feature selection in case we have a huge number of features.


![Screenshot 2022-11-11 225337.png](https://cdn.hashnode.com/res/hashnode/image/upload/v1668187439157/7FZy0ZYIo.png align="left")

- Methods like Cross-validation, Stepwise Regression are there to handle overfitting and perform feature 
selection work well with a small set of features. These techniques are good when we are dealing with a 
large set of features.

- Along with shrinking coefficients, the **lasso performs feature selection**, as well. (Remember the 
‘**selection**‘ in the lasso full-form?) Because some of the coefficients become exactly zero, which is 
equivalent to the particular feature being excluded from the model.