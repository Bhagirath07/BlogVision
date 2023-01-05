# #26 Machine Learning & Data Science Challenge 26

# What is BaysianSearchCV?

* Bayesian search, in contrast to the grid and random search, keeps track of past evaluation results, which they use to form a probabilistic model mapping hyperparameters to a probability of a score on the objective function.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672661016370/113dad5e-9d82-4be2-be55-dea959a93f1f.png align="center")

### Code Example:

```python
from skopt import BayesSearchCV 

opt = BayesSearchCV( 
    SVC(), 
    { 
        'C': (1e-6, 1e+6, 'log-uniform'), 
        'gamma': (1e-6, 1e+1, 'log-uniform'), 
        'degree': (1, 8), # integer valued parameter 
        'kernel': ['linear', 'poly', 'rbf'] 
    }, 
    n_iter=32, 
    cv=3
)
```