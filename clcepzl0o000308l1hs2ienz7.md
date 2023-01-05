# #24 Machine Learning & Data Science Challenge 24

# What is RandomizedSearchCV?

* Randomized search CV is used to **perform a random search on hyperparameters.**
    
* Randomized search CV uses a **fit and score method**, **predict proba**, **decision\_func**, **transform**, etc...
    
* The parameters of the estimator used to apply these methods are **optimized by cross-validated search over parameter settings**.
    
* In contrast to GridSearchCV, not all parameter values are tried out, but rather a fixed number of parameter settings is sampled from the specified distributions.
    
* The number of parameter settings that are tried is given by **n\_iter**.
    

### Code Example :

```python
class sklearn.model_selection.RandomizedSearchCV 
(
    estimator, 
    param_distributions, 
    n_iter=10, 
    scoring=None, 
    fit_params=None, 
    n_jobs=None, 
    iid=’warn’, 
    refit=True, 
    cv=’warn’, 
    verbose=0, 
    pre_dispatch=‘2n_jobs’, 
    random_state=None, 
    error_score=’raise-deprecating’, 
    return_train_score=’warn’
)
```