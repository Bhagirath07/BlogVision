# #48 Machine Learning & Data Science Challenge 48

# What are upsampling and downsampling with examples?

**The classification data set with skewed class proportions is called an imbalanced data set.**

* Classes that make up a large proportion of the data sets are called majority classes. Those makeup smaller proportions are minority classes.
    

Degree of imbalance Proportion of Minority Class:

1. **Mild 20-40% of the data set**
    
2. **Moderate 1-20% of the data set**
    
3. **Extreme &lt;1% of the data set**
    

* If we have an imbalanced data set, first try training on the true distribution. If the model works well and generalizes, you are done! If not, try the following-up sampling and down-sampling techniques.
    

### 1\. Up-sampling:

**Upsampling is the process of randomly duplicating observations from the minority class to reinforce its signal.**

First, we will import the resampling module from Scikit-Learn:

* **Module for resampling Python**
    

From sklearn.utils import resample Next, we will create a new Data Frame with an up-sampled minority class.

Here are the steps:

1. First, we will separate observations from each class into different Data Frames.
    
2. Next, we will resample the minority class with replacement, setting the number of samples to match that of the majority class.
    
3. Finally, we'll combine the up-sampled minority class Data Frame with the original majority class Data Frame.
    

### 2\. Down-sampling:

**Downsampling involves randomly removing observations from the majority class to prevent its signal from dominating the learning algorithm.**

The process is similar to that of sampling. Here are the steps:

1. First, we will separate observations from each class into different Data Frames.
    
2. Next, we will resample the majority class without replacement, setting the number of samples to match that of the minority class.
    
3. Finally, we will combine the down-sampled majority class Data Frame with the original minority class Data Frame.