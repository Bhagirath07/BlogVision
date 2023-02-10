# #104 Machine Learning & Data Science Challenge 104

# What is the Moving Average?

**The moving average model is probably the most naive approach to time series modeling.**

* This model states that the next observation is the mean of all past observations. Although simple, this model might be surprisingly good, and it represents a good starting point.
    
* Otherwise, the moving average can be used to identify interesting trends in the data.
    
* We can define a window to apply the moving average model to smooth the time series and highlight different trends.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675586713467/cd87a1e7-d675-4de5-b585-51f6bfa070bb.png align="center")

* In the plot above, we applied the moving average model to a 24h window.
    
* The green line smoothed the time series, and we can see that there are two peaks in the 24h period.
    
* The longer the window, the smoother the trend will be.
    
* Below is an example of a moving average on a smaller window.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675586733693/bffdb956-182f-430b-bc35-547311d8c837.png align="center")