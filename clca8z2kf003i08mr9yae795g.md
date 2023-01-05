# #16 Machine Learning & Data Science Challenge 16

# What are Ensemble Methods?

## Bagging and Boosting:

* **Decision trees have been around for a long time and are also known to suffer from bias and variance.**
    
* You will have a large bias with simple trees and a large variance with complex trees.
    

## Ensemble methods:

* Which combines several decision trees to produce better predictive performance than utilizing a single decision tree.
    
* The main principle behind the ensemble model is that a group of weak learners come together to form a strong learner.
    
* Two techniques to perform ensemble decision trees:
    

1. **Bagging**
    
2. **Boosting**
    

### Bagging (Bootstrap Aggregation):

* It is used when our goal is to reduce the variance of a decision tree. Here the idea is to create several subsets of data from the training sample chosen randomly with replacement.
    
* Now, each collection of subset data is used to train their decision trees. As a result, we end up with an ensemble of different models.
    
* An average of all the predictions from different trees is used which is more robust than a single decision tree.
    

### Boosting:

* It is another ensemble technique to create a collection of predictors. In this technique, learners are learned sequentially with early learners fitting simple models to the data and then analyzing data for errors.
    
* In other words, we fit consecutive trees (random sample), and at every step, the goal is to solve for net error from the prior tree.
    
* When a hypothesis misclassifies an input, its weight is increased, so that the next hypothesis is more likely to classify it correctly.
    
* Combining the whole set at the end converts weak learners into a better-performing model.
    

* The different types of boosting algorithms are:
    
    1. **AdaBoost**
        
    2. **Gradient Boosting**
        
    3. **XGBoost**