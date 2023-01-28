# #74 Machine Learning & Data Science Challenge 74

# What are you under by the vanishing gradient problem and how can we solve that?

### The problem:

As more layers using specific activation functions are added to neural networks, the gradients of the loss function approach zero, making the networks tougher to train.

### Why:

- Certain activation functions, like the sigmoid function, squishes an ample input space into a small input space between 0 and 1. 

- Therefore, a large change in the input of the sigmoid function will cause a small 
change in the output. Hence, the derivative becomes small.

- For shallow networks with only a few layers that use these activations, this isn’t a big problem. 

- However, when more layers are used, it can cause the gradient to be too small for training to work effectively.

- However, when n hidden layers use an activation like the sigmoid function, n small derivatives are multiplied together.

- Thus, the gradient decreases exponentially as we propagate down to the initial layers.


### Solutions:

- The simplest solution is to use other activation functions, such as ReLU, which doesn’t cause a small derivative.

- Residual networks are another solution, as they provide residual connections straight to earlier layers.

- Finally, batch normalization layers can also resolve the issue.
