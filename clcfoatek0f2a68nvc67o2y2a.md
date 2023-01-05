# #25 Machine Learning & Data Science Challenge 25

# What is GridSearchCV?

* Grid search is **the process of performing hyperparameter tuning to determine the optimal values for a given model.**
    

### Code Example:

```python
from sklearn.model_selection import GridSearchCV 

from sklearn.svm import SVR 

gsc = GridSearchCV( 

    estimator=SVR(kernel='rbf'),
    param_grid={
    'C': [0.1, 1, 100, 1000], 
    'epsilon': [0.0001, 0.0005, 0.001, 0.005, 0.01, 0.05, 0.1, 0.5, 1, 5, 10],       
    'gamma': [0.0001, 0.001, 0.005, 0.1, 1, 3, 5] 
    }, 
    cv=5, 
    scoring='neg_mean_squared_error', 
    verbose=0, 
    n_jobs=-1
)
```

**Grid search runs the model on all the possible ranges of hyperparameter values and outputs the best model.**