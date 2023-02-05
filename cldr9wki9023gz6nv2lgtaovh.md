# #94 Machine Learning & Data Science Challenge 94

# What is the process to make data stationery from non-stationary time series?

The two most common ways to make a non-stationary time series stationary are:

* **Differencing**
    
* **Transforming**
    

Let us look at some details for each of them:

## Differencing:

To make your series stationary, you take a difference between the data points. So let us say, your original time series was:

* X1, X2, X3,...........Xn
    

Your series with a difference of degree 1 becomes:

* (X2 - X1, X3 - X2, X4 - X3,.......Xn - X(n-1)
    

Once, you make the difference, plot the series and see if there is any improvement in the ACF curve.

If not, you can try a second or even a third-order differencing. Remember, the more you differentiate, the more complicated your analysis is becoming.

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675188226834/91748d01-6147-4680-8266-690f993dc8d0.png align="center")

## Transforming:

If we cannot make a time series stationary, you can try out transforming the variables.

* Log transform is probably the most commonly used transformation if we see the diverging time series.
    
* However, it is suggested that you use transformation only in case differencing is not working.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675188243498/d887e755-ec30-4484-a0f9-6db9cc10919a.png align="center")