# #40 Machine Learning & Data Science Challenge 40

# The tradeoff between bias and variances, the relationship between them.

**Whenever we discuss model prediction, it’s important to understand prediction errors (bias and variance).**

**The prediction error for any machine learning algorithm can be broken down into three parts:**

* **Bias Error**
    
* **Variance Error**
    
* **Irreducible Error**
    

### Bias:

* **Bias means that the model favors one result more than the others.** Bias is the simplifying assumptions made by a model to make the target function easier to learn.
    
* The model with high bias pays very little attention to the training data and oversimplifies the model.
    
* It always leads to a high error in training and test data.
    

### Variance:

* **Variance is the amount that the estimate of the target function will change if different training data was used.**
    
* The model with high variance pays a lot of attention to training data and does not generalize on the data which it hasn’t seen before. As a result, such models perform very well on training data but have high error rates on test data.
    

### **Irreducible:**

* **The irreducible error cannot be reduced regardless of what algorithm is used.**
    
* It is the error introduced from the chosen framing of the problem and may be caused by factors like unknown variables that influence the mapping of the input variables to the output variable.
    

> ![Overfitting](https://cdn.hashnode.com/res/hashnode/image/upload/v1672827913140/47a76f2a-1262-40dc-9faf-22c843949e41.png align="center")

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672827922105/e7703973-2bf9-4686-aca0-e0b4efafb911.png align="center")

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672827929167/40d03f54-80cc-4846-978e-770ed4c7d58e.png align="center")

So, **the end goal is to come up with a model that balances both Bias and Variance. This is called Bias Variance Trade-off.**

* To build a good model, we need to find a good balance between bias and variance such that it minimizes the total error.