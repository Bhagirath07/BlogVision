# #50 Machine Learning & Data Science Challenge 50

# What is the Central limit theorem?

### Central Limit Theorem:

#### Definition:

**The theorem states that as the size of the sample increases, the distribution of the mean across multiple samples will approximate a Gaussian distribution (Normal).**

* Generally, sample sizes equal to or greater than 30 are considered sufficient for the CLT to hold.
    
* It means that the distribution of the sample means is normally distributed.
    
* The average of the sample means will be equal to the population mean. This is the key aspect of the theorem.
    

#### Assumptions:

1. The data must follow the randomization condition. It must be sampled randomly
    
2. Samples should be independent of each other. One sample should not influence the other samples
    
3. Sample size should be no more than 10% of the population when sampling is done without replacement
    
4. The sample size should be sufficiently large. The mean of the sample means is denoted as:
    

> $$µ X̄= µ$$

Where,

* **µ X̄= Mean of the sample means**
    
* **µ= Population mean** and, the standard deviation of the sample mean is denoted as:
    

> $$σ X̄= σ/sqrt(n)$$

Where,

* **σ X̄= Standard deviation of the sample mean**
    
* **σ = Population standard deviation**
    
* **n = sample size**
    

**A sufficiently large sample size can predict the characteristics of a population accurately.**

* For Example, we shall take uniformly distributed data:
    

#### Randomly distributed data:

**Even for randomly (Exponential) distributed data the plot of the means is normally distributed.**

* The advantage of CLT is that we need not worry about the actual data since the means of it will always be normally distributed. With this, we can create component intervals, and perform T-tests and ANOVA tests from the given samples.