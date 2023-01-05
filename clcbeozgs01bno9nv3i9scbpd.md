# #18 Machine Learning & Data Science Challenge 18

# **What are Naive Bayes Classification and Gaussian Naive Bayes?**

* Bayes’ Theorem finds the probability of an event occurring given the probability of another event that has already occurred.
    
* Bayes’ theorem is stated mathematically as the following equation:
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672395979234/2a7fa25a-2bbf-411b-b225-22dce3f93f73.png align="center")

### Naive Bayes Classification:

1. We assume that no pair of features are dependent. For example, the temperature being ‘Hot’ has nothing to do with the humidity, and the outlook is ‘Rainy’ does not affect the winds. Hence, the features are assumed to be independent.
    
2. Secondly, each feature is given the same weight (or importance). For example, knowing the only temperature and humidity alone can’t predict the outcome accurately. None of the attributes is irrelevant and assumed to be contributing equally to the outcome.
    

### Gaussian Naive Bayes:

* Continuous values associated with each feature are assumed to be distributed according to a Gaussian distribution.
    
* A Gaussian distribution is also called Normal distribution.
    
* When plotted, it gives a bell-shaped curve that is symmetric about the mean of the feature values as shown below:
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672396009666/6b98ae50-0277-4571-a4ad-efe11ecece36.png align="center")

* This is as simple as calculating the mean and standard deviation values of each input variable (x) for each class value.
    

$$Mean (x) = 1 / n * sum(x)$$

* Where n is the number of instances, and x is the value for an input variable in your training data.
    
* We can calculate the standard deviation using the following equation:
    

$$Standard Deviation (x) = sqrt (1/n * sum(xi-mean(x)^2 ))$$