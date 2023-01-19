# #59 Machine Learning & Data Science Challenge 59

# How do we assign weights in deep learning?

* We already know that in a neural network, weights are usually initialized randomly and that kind of initialization takes a fair/significant amount of repetitions to converge to the least loss and reach the ideal weight matrix.
    
* The problem is, that kind of initialization is prone to vanishing or exploding gradient problems.
    

#### General ways to make it initialize better weights:

**A) ReLu activation function in the deep nets.**

1. Generate a random sample of weights from a Gaussian distribution having a mean of 0 and a standard deviation of 1.
    
2. Multiply the sample with the square root of (2/ni). Where ni is the number of input units for that layer.
    

**B) Likewise, if you’re using the Tanh activation function.**

1. Generate a random sample of weights from a Gaussian distribution having a mean of 0 and a standard deviation of 1.
    
2. Multiply the sample with the square root of (1/ni) where ni is several input units for that layer.