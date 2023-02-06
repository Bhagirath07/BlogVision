# #96 Machine Learning & Data Science Challenge 96

# What are ACF and PACF?

## ACF:

* **It is a (complete) auto-correlation function that gives us the values of the auto-correlation of any series with lagged values.** We plot these values along with a confidence band.
    
* We have an ACF plot. In simple terms, it describes how well the present value of the series is related to its past values.
    
* A time series can have components like a trend, seasonality, cyclic and residual.
    
* ACF considers all the components while finding correlations; hence, it’s a ‘complete auto-correlation plot’.
    

## PACF:

* I**t is a partial autocorrelation function. Instead of finding correlations of present with lags like ACF, it finds the correlations of the residuals with the next lag value thus ‘partial’ and not ‘complete’ as we remove already found variations before we find the next correlation.**
    
* So if there are any hidden pieces of information in the residual which can be modeled by the next lag, we might get a good correlation, and we’ll keep that next lag as a feature while modeling.
    
* Remember, while modeling we don’t want to keep too many correlated features, as that can create multicollinearity issues. Hence we need to retain only relevant features.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1675579296579/5937d242-fd03-4e73-8ba5-cc38d42e170a.png align="center")