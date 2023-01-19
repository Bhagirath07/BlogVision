# #60 Machine Learning & Data Science Challenge 60

# What optimizer is deep learning, and which one is the best?

* Deep learning is an iterative process. With so many hyperparameters to tune or methods to try, it is important to be able to train models fast, to quickly complete the iterative cycle.
    
* This is the key to increasing the speed and efficiency of a machine-learning team.
    
* Hence the importance of optimization algorithms such as stochastic gradient descent, min-batch gradient descent, and gradient descent with momentum and the Adam optimizer.
    

**Adam optimizer is the best one.**

* Given an algorithm f(x), it helps in either minimization or maximization of the value of f(x). In this context of deep learning, we use optimization algorithms to train the neural network by optimizing the cost function J.
    

**The cost function is defined as:**

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673550012786/b56aabf8-33fc-44e3-badd-0a3de2421b6f.png align="center")

* The value of the cost function J is the mean of the loss L between the predicted value y’ and the actual value y.
    
* The value y” is obtained during the forward propagation step and makes use of the Weights W and biases b of the network. With the help of optimization algorithms, we minimize the value of Cost Function J by updating the values of trainable parameters W and b.