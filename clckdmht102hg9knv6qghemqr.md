# #33 Machine Learning & Data Science Challenge 33

# What is the pipeline in sklearn?

* **A pipeline is what chains several steps together, once the initial exploration is done.**
    
* For example, some codes are meant to transform features—normalize numerically, turn text into vectors, or fill up missing data, and they are transformers; other codes are meant to predict variables by fitting an algorithm, such as random forest or support vector machine, they are estimators.
    
* Pipeline chains all these together, which can then be **applied to training data** in the block.
    

#### **Example of a pipeline that imputes data with the most frequent value of each column, and then fits a decision tree classifier.**

```python
from sklearn.pipeline import Pipeline 
steps = [
    (
        'imputation', 
        Imputer(
                missing_values='NaN', 
                strategy = 'most_frequent', 
                axis=0
                )
    ), 
    (
        'clf', 
        DecisionTreeClassifier()
    )
] 
pipeline = Pipeline(steps) 
clf = pipeline.fit(X_train,y_train)
```

#### **Instead of fitting to one model, it can be looped over several models to find the best one.**

```python
classifiers = [ 
    KNeighborsClassifier(5), 
    RandomForestClassifier(), 
    GradientBoostingClassifier()
] 
for clf in classifiers: 
steps = [(
        'imputation', 
        Imputer(missing_values='NaN', 
                strategy = 'most_frequent', 
                axis=0)
        ), 
        ('clf', clf)
] 
pipeline = Pipeline(steps)
```

#### **I also learned the pipeline itself can be used as an estimator and passed to cross-validation or grid search.**

```python
from sklearn.model_selection import KFold 
from sklearn.model_selection import cross_val_score 

kfold = KFold(n_splits=10, random_state=seed) 
results = cross_val_score(pipeline, X_train, y_train, cv=kfold) 

print(results.mean())
```