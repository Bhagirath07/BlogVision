# #39 Machine Learning & Data Science Challenge 39

# What are the encoding techniques you have applied with examples?

* In many practical data science activities, the data set will contain categorical variables.
    
* These variables are typically stored as text values.
    
* Since machine learning is based on mathematical equations, it would cause a problem when we keep categorical variables as is.
    
* Let's consider the following dataset of fruit names and their weights.
    

#### Some of the common encoding techniques are:

### Label encoding:

* In label encoding, we map each category to a number or a label.
    
* The labels chosen for the categories have no relationship.
    
* So, categories that have some ties or are close to each other lose such information after encoding.
    

### One-hot encoding:

* In this method, we map each category to a vector that contains 1 and 0 denoting the presence of the feature or not.
    
* The number of vectors depends on the categories which we want to keep.
    
* For high cardinality features, this method produces a lot of columns that slow down learning significantly.