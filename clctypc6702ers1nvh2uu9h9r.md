# #47 Machine Learning & Data Science Challenge 47

# What is the difference between normalization and Standardization with example?

**In Machine Learning, every practitioner knows that feature scaling is an important issue.**

* The two most discussed scaling methods are Normalization and Standardization.
    
* Normalization typically means it rescales the values into a range of \[0,1\].
    
* It is an alternative approach to Z-score normalization (or standardization) is the so-called Min-Max scaling (often also called “normalization” - a common cause for ambiguities).
    
* In this approach, the data is scaled to a fixed range - usually 0 to 1. Scikit-Learn provides a transformer called MinMaxScaler for this.
    
* A Min-Max scaling is typically done via the following equation:
    

$$Xnorm = X-Xmin/Xmax-Xmin$$

### Example with sample data:

#### Before Normalization:

Attribute Price in Dollars Storage Space Camera

* Mobile 1 250 16 12
    
* Mobile 2 200 16 8
    
* Mobile 3 300 32 16
    
* Mobile 4 275 32 8
    
* Mobile 5 225 16 16
    

#### After Normalization:

Attribute Price in Dollars Storage Space Camera (Values range from 0-1 which is working as expected)

* Mobile 1 0.5 0 0.5
    
* Mobile 2 0 0 0
    
* Mobile 3 1 1 1
    
* Mobile 4 0.75 1 0
    
* Mobile 5 0.25 0 1
    

**Standardization (or Z-score normalization) typically means rescales data to have a mean of 0 and a standard deviation of 1 (unit variance) Formula:**

* Z or X\_new=(x−μ)/σ where μ is the mean (average), and σ is the standard deviation from the mean; standard scores (also called z scores)
    

**Scikit-Learn provides a transformer called StandardScaler for standardization Example:**

* Let’s take an approximately normally distributed set of numbers: 1, 2, 2, 3, 3, 3, 4, 4, and 5. Its mean is 3, and its standard deviation is 1.22.
    
* Now, let’s subtract the mean from all data points.
    
* we get a new data set of -2, -1, -1, 0, 0, 0, 1, 1, and 2.
    
* Now, let’s divide each data point by 1.22. As you can see in the picture below, we get -1.6, -0.82, -0.82, 0, 0, 0, 0.82, 0.82, and 1.63.