# #14 Machine Learning & Data Science Challenge 14

# What is the Random Forest Algorithm?

* Random Forest is **an ensemble machine-learning algorithm that follows the bagging technique.**
    
* The base estimators in the random forest are decision trees. Random forest randomly selects a set of Features to decide the best split at each node of the decision tree.
    

### Looking at it step-by-step, this is what a random forest model does:

1. Random subsets are created from the original dataset (**bootstrapping**).
    
2. At each node in the decision tree, only a random set of features is considered to decide the best split.
    
3. A decision tree model is fitted on each of the subsets.
    
4. The final prediction is calculated by averaging the predictions from all decision trees.
    

* To summarize, **the Random forest randomly selects data points and features and builds multiple trees (Forest).**
    
* Random Forest is used for **feature importance selection.**
    
* The attribute (.feature\_importances\_) is used to **find feature importance.**
    

### Some Important Parameters:-

1. **n\_estimators**:
    
    * It defines the number of decision trees created in a random forest.
        
2. **criterion**:
    
    * "**Gini**" or "**Entropy**."
        
3. **min\_samples\_split**:
    
    * It is used to define the minimum number of samples required in a leaf node before a split is attempted.
        
4. **max\_features**:
    
    * It defines the maximum number of features allowed for the split in each decision tree.
        
5. **n\_jobs**:
    
    * The number of jobs to run in parallel for both fits and predict. Always keep (-1) to use all the cores for parallel processing.