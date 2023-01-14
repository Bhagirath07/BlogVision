# #49 Machine Learning & Data Science Challenge 49

# What is the statistical test for data validation with an example, Chi-square, ANOVA test, Z statics, T statics, F statics, and Hypothesis Testing?

* Before discussing the different statistical tests, we need to get a clear understanding of what a null hypothesis is. A null hypothesis proposes that no significant difference exists in the set of a given observation.
    

**Null: Two samples' mean is equal.**

**Alternate: Two samples' mean is not equal.**

* For rejecting the null hypothesis, a test is calculated.
    
* Then the test statistic is compared with a critical value, and if found to be greater than the critical value, the hypothesis will be rejected.
    

### Critical Value:

**Critical values are the point beyond which we reject the null hypothesis.**

* Critical value tells us, what is the probability of N number of samples, belonging to the same distribution.
    
* A higher, critical value means a lower probability of N number of samples belonging to the same distribution.
    

Critical values can be used to do hypothesis testing in the following way.

1. Calculate the test statistic
    
2. Calculate critical values based on the significance level of alpha
    
3. Compare test statistics with critical values
    

**IMP-If the test statistic is lower than the critical value, accept the hypothesis or else reject the hypothesis.**

### Chi-Square Test:-

**A chi-square test is used if there is a relationship between two categorical variables.**

* The chi-Square test is used to determine whether there is a significant difference between the expected frequency and the observed frequency in one or more categories.
    
* Chi-square is also called the non-parametric test as it will not use any parameter.
    

### ANOVA test:

**ANOVA also called an analysis of variance, is used to compare multiple (three or more) samples with a single test.**

* Useful when there are more than three populations. Anova compares the variance within and between the groups of the population.
    
* If the variation is much larger than the within variation, the means of different samples will not be equal.
    
* If the between and within variations are approximately the same size, then there will be no significant difference between sample means.
    

#### Assumptions of ANOVA:

1. All populations involved follow a normal distribution.
    
2. All populations have the same variance (or standard deviation).
    
3. The samples are randomly selected and independent of one another.
    

**ANOVA uses the mean of the samples or the population to reject or support the null hypothesis. Hence it is called parametric testing.**

### Z Statics:

In a z-test, **the samples are assumed to be normally distributed.**

* A z score is calculated with population parameters as “population mean” and “population standard deviation” and it is used to validate a hypothesis that the sample drawn belongs to the same population.
    
* The statistics used for this hypothesis testing is called z-statistic, the score for which is calculated as z = (x — μ) / (σ / √n), where x= sample mean μ = population mean σ / √n = population standard deviation If the test statistic is lower than the critical value, accept the hypothesis or else reject the hypothesis
    

### T Statics:

**A t-test was used to compare the mean of the given samples. Like the z-test, the t-test also assumed a normal distribution of the samples.**

* A t-test is used when the population parameters (mean and standard deviation) are unknown.
    

There are three versions of the t-test;

1. Independent samples t-test which compares means for two groups.
    
2. Paired sample t-test which compares mean from the same group at different times.
    
3. Sample t-test, which tests the mean of the single group against the known mean.
    

* The statistic for hypothesis testing is called t-statistic, the score for which is calculated as;
    

$$t = (x1 — x2) / (σ / √n1 + σ / √n2)$$

Where,

* **x1 = It is the mean of sample A**
    
* **x2 = mean of sample B**
    
* **n1 = size of sample 1**
    
* **n2 = size of sample 2**
    

### F Statics:

**The F-test is designed to test if the two population variances are equal. It compares the ratio of the two variances.**

* Therefore, if the variances are equal, then the ratio of the variances will be 1.
    
* The F-distribution is the ratio of two independent chi-square variables divided by their respective degrees of freedom.
    

> $$F = s1^2 / s2^2$$

Where **s1^2 &gt; s2^2.**

* If the null hypothesis is true, then the F-test statistic given above can be simplified.
    
* This ratio of sample variances will be tested by statistics used. If the null hypothesis is false, then we will reject the null hypothesis that the ratio was equal to 1 and our assumption that they were equal.