# #105 Machine Learning & Data Science Challenge 105

# What is Exponential smoothing?

**Exponential smoothing uses similar logic to the moving average, but this time, different decreasing weight is assigned to each observation.**

* We can also say, less importance is given to the observations as we move further from the present.
    
* Mathematically, exponential smoothing is expressed as:
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675587108812/da906551-9214-4966-b422-72a004304fe6.png align="center")

* Here, alpha is the smoothing factor that takes values between 0 to 1. It determines how fast the weight will decrease for the previous observations.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675587319988/7297768a-e29c-4be1-91af-505d766a2655.png align="center")

* From the above plot, the dark blue line represents the exponential smoothing of the time series using a smoothing factor of 0.3, and the orange line uses a smoothing factor of 0.05. As we can see, the smaller the smoothing factor, the smoother the time series will be.
    
* Because as the smoothing factor approaches 0, we approach the moving average model.