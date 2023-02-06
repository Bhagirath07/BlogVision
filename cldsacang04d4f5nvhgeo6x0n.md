# #95 Machine Learning & Data Science Challenge 95

# What is the process for checking static data?

### Stationary series:

**It is one in which the properties – mean, variance, and covariance does not vary with time.**

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675578807743/7a8f3f2d-4951-45bb-a203-25f22f56a623.png align="center")

Let us get an idea with these three plots:

* In the first plot, we can see that the mean varies (increases) with time, which results in an upward trend. This is the non-stationary series.
    

For the series classification as stationary, it should not exhibit the trend.

* Moving on to the second plot, we do not see a trend in the series, but the series variance is a time function. As mentioned previously, a stationary series must have a constant variance.
    
* If we look at the third plot, the spread becomes closer, as the time increases, which implies that covariance is a function of time.
    

These three plots refer to the non-stationary time series. Now give your attention to the fourth:

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675578812874/b2b8c520-3fbe-472f-baa1-bb2bef477455.png align="center")

* In this case, Mean, Variance, and Covariance are constant with time. This is what a stationary time series looks like.
    
* Most statistical models require the series to be stationary to make an effective and precise prediction.
    

The various process you can use to find out whether your data is stationary or not by the following terms:

1. **Visual Test**
    
2. **Statistical Test**
    
3. **ADF(Augmented Dickey-Fuller) Test**
    
4. **KPSS(Kwiatkowski-Phillips-Schmidt-Shin) Test**