# #15 Machine Learning & Data Science Challenge 15

# What are the Variance and Bias tradeoffs?

* In predicting models, the prediction error is composed of two different errors
    

1. **Bias**
    
2. **Variance**
    

* **It is important to understand the variance and bias trade-off which tells about minimizing the Bias and Variance in the prediction and avoids overfitting & fitting of the model.**
    

### Bias:

* It is the difference between the expected or average prediction of the model and the correct value that we are trying to predict.
    
* Imagine if we are trying to build more than one model by collecting different data sets, and later on, evaluating the prediction, we may end up with different predictions for all the models.
    
* So, bias is something that measures how far these model predictions are from the correct prediction. It always leads to a high error in training and test data.
    

### Variance:

* Variability of a model prediction for a given data point.
    
* We can build the model multiple times, so the variance is how much the predictions for a given point vary between different realizations of the model.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672386499580/3599c44f-2268-45cc-9b9e-60ff9dbb13a3.png align="center")

### For example:

* **Voting Republican - 13 Voting Democratic - 16 Non-Respondent - 21 Total - 50 The probability of voting Republican is 13/(13+16), or 44.8%. We put out our press release that the Democrats are going to win by over 10 points; but, when the election comes around, it turns out they lose by 10 points. That certainly reflects poorly on us. Where did we go wrong in our model?**
    

* **Bias scenarios**:
    
    * using a phonebook to select participants in our survey is one of our sources of bias.
        
    * Only surveying certain classes of people, skews the results in a way that will be consistent if we repeated the entire model-building exercise.
        
    * Similarly, not following up with respondents is another source of bias, as it consistently changes the mixture of responses we get. On our bulls-eye diagram, these move us away from the center of the target, but they would not result in an increased scatter of estimates.
        
    
* **Variance scenarios**:
    
    * the small sample size is a source of variance.
        
    * If we increased our sample size, the results would be more consistent each time we repeated the survey and prediction.
        
    * The results still might be highly inaccurate due to our large sources of bias, but the variance of predictions will be reduced.
        

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672386759860/18997559-ed0c-4321-ab80-1fda85e38e74.png align="center")