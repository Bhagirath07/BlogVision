# #99 Machine Learning & Data Science Challenge 99

# What are AIC and BIC in time series?

**Akaike’s information criterion (AIC) compares the quality of a set of statistical models to each other.**

* For example, you might be interested in what variables contribute to low socioeconomic status and how the variables contribute to that status.
    
* Let’s say you create several regression models for various factors like education, family size, or disability status; The AIC will take each model and rank them from best to worst.
    
* The “best” model will be the one that neither under-fits nor over-fits.
    

* **AIC**
    
* **K = number of estimated parameters in the model**
    
* **L = Maximised likelihood function for the estimated model**
    

$$AIC = 2k - 2ln(L)$$

The Bayesian Information Criterion (BIC) can be defined as:

$$k*log(n)- 2log(L(θ̂))$$

* K is the number of parameters that your model estimates.
    
* θ is the set of all parameters.
    
* L (θ̂) represents the likelihood of the model tested, when evaluated at maximum likelihood values of θ.