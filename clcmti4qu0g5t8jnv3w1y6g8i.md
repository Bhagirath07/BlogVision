# #37 Machine Learning & Data Science Challenge 37

# How to evaluate that data does not have any outliers?

**In statistics, outliers are data points that don’t belong to a certain population. It is an abnormal observation that lies far away from other values. An outlier is an observation that diverges from otherwise well-structured data.**

## Detection:

### Method 1 — Standard Deviation:

* In statistics, If a data distribution is approximately normal, then about 68% of the data values lie within one standard deviation of the mean, about 95% are within two standard deviations, and about 99.7% lie within three standard deviations.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672826218955/1b7990ee-682d-4961-8873-8f71e1f0e6ac.png align="center")

* Therefore, if you have any data point that is more than 3 times the standard deviation, then those points are very likely to be anomalous or outliers.
    

### Method 2 — Boxplots:

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672826236140/0b9b1599-7153-431e-8d79-04a5bf5c5cb1.png align="center")

* Box plots are a graphical depiction of numerical data through their quantiles. It is a very simple but effective way to visualize outliers.
    
* Think about the lower and upper whiskers as the boundaries of the data distribution.
    
* Any data points that show above or below the whiskers can be considered outliers or anomalous.
    

### Method 3 — Violin Plots:

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672826242343/324d7514-d7d7-4b7f-8b8d-e7ef7fabab9f.png align="center")

* Violin plots are similar to box plots, except that they also show the probability the density of the data at different values, usually smoothed by a kernel density estimator.
    
* Typically a violin plot will include all the data that is in a box plot: sub point- a marker for the median of the data, a box or marker indicating the interquartile range, and possibly all sample points if the number of samples is not too high.
    

### Method 4 - Scatter Plots:

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672826254338/26f87e76-8fa8-4796-bd19-668626ed67ea.png align="center")

* A scatter plot is a type of plot or mathematical diagram using Cartesian coordinates to display values for typically two variables for a set of data.
    
* The data are displayed as a collection of points, each having the value of one variable determining the position on the horizontal axis and the value of the other variable determining the position on the vertical axis.
    
* The points which are very far away from the general spread of data and have very few neighbors are considered to be outliers.