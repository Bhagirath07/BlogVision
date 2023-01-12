# #46 Machine Learning & Data Science Challenge 46

# What is the data normalization method you have applied, and why?

## Normalization

**It is a technique often applied as part of data preparation for machine learning.**

* The goal of normalization is **to change the values of numeric columns in the dataset to a common scale, without distorting differences in the ranges of values.**
    
* For machine learning, **every dataset does not require normalization.**
    
* It is required only when features have different ranges.
    

In simple words, when multiple attributes are there, but attributes have values on different scales, this may lead to poor data models while performing data mining operations.

* So they are normalized to bring all the attributes on the same scale, usually something between (0,1).
    
* It is not always a good idea to normalize the data since we might lose information about maximum and minimum values.
    

#### For example, ML algorithms such as Linear Regression or Support Vector Machines typically converge faster on normalized data.

* But on algorithms like K-means or K Nearest Neighbours, normalization could be a good choice or a bad one depending on the use case since the distance between the points plays a key role here.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673376322603/cee8930e-a75c-4164-9fb5-6b9c3e48427c.png align="center")

## Types of Normalisation

### 1\. Min-Max Normalization:

**In most cases, standardization is used feature-wise**

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673376420171/1189dc92-188a-42b2-a8ef-240432035807.png align="center")

### 2\. Z-score normalization:

**In this technique, values are normalized based on the mean and standard deviation of the data.**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673376682617/41bc9492-6246-495c-8670-6607c533e471.png align="center")

* v’, v is the new and old of each entry in data respectively. σA, A is the standard deviation and mean of A respectively.
    
* Standardization (or Z-score normalization) is that the features will be rescaled so that they’ll have the properties of a standard normal distribution with μ=0 and σ=1 where μ is the mean (average) and σ is the standard deviation from the mean;
    
* Standard scores (also called z scores) of the samples are calculated as follows:
    

$$z=(x−μ)/σ$$