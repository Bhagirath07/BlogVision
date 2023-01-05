# #13 Machine Learning & Data Science Challenge 13

# How to handle a decision tree for numerical and categorical data?

* Decision trees can handle both categorical and numerical variables at the same time as features. There is not any problem with doing that.
    
* Every split in a decision tree is based on a feature.
    
    1. **If the feature is categorical, the split is done with the elements belonging to a particular class.**
        
    
    1. **If the feature is continuous, the split is done with the elements higher than a threshold.**
        
    
* At every split, the decision tree will take the best variable at that moment. This will be done according to an impurity measure with the split branches. And the fact that the variable used to do split is categorical or continuous is irrelevant (in fact, decision trees categorize continuous variables by creating binary regions with the threshold).
    
* At last, the good approach is to always convert your **categoricals to continuous** using **LabelEncoder** or **OneHotEncoding.**