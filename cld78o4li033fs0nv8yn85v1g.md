# #66 Machine Learning & Data Science Challenge 66

# How to initialize biases in deep learning?

- It is possible and common to initialize the biases to be zero since the random numbers in the weights provide the asymmetry braking.

- For ReLU non-linearities, some people like to use small constant values such as 0.01 for all biases because this ensures that all ReLU units fire in the beginning, 
therefore obtain, and propagate some gradient.

- However, it is unclear if this provides a consistent improvement (in fact some results seem to indicate that this performs worst) and it is more commonly used to use 0 bias initialization.
