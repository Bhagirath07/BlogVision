# #70 Machine Learning & Data Science Challenge 70

# What is a Dropout in a Neural network?

**Dropout refers to ignoring units during the training phase of a certain set of neurons which is chosen randomly.**

* These units are not considered during the particular forward or backward pass.
    
* More technically, at each training stage, individual nodes are either dropped out of the net with probability 1-p or kept with probability p, so that a reduced network is left; incoming and outgoing edges to a dropped-out node are also removed.
    
* We need Dropout to prevent over-fitting.
    
* A dropout is an approach to regularization in neural networks which helps to reduce interdependency learning amongst the neurons.
    

### Where to use?

**Dropout is implemented per layer in a neural network.**

* It can be used with most types of layers, such as dense fully connected layers, convolutional layers, and recurrent layers such as the long short-term memory network layer.
    
* Dropout may be implemented on any or all hidden layers in the network as well as the visible or input layer. It is not used on the output layer.
    

### Benefits:

1. Dropout forces a neural network to learn more robust features that are very useful in conjunction with different random subsets of the other neurons.
    
2. Dropout generally doubles the number of iterations required to converge. However, the training time for each epoch is less.