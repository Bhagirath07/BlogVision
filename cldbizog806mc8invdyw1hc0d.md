# #72 Machine Learning & Data Science Challenge 72

# What do you understand by activation function and error functions?

## Error functions:

* In most learning networks, an error is calculated as the difference between the predicted output and the actual output.
    
* The function that is used to compute this error is known as Loss Function J(.). Different loss functions will give different errors for the same prediction, and thus have a considerable effect on the performance of the model.
    

* One of the most widely used loss functions is mean square error, which calculates the square of the difference between the actual values and predicted value.
    
* Different loss functions are used to deal with different types of tasks, i.e. regression and classification.
    

### Regressive loss functions:

1. Mean Square Error
    
2. Absolute error
    
3. Smooth Absolute Error
    

### Classification loss functions:

1. Binary Cross-Entropy
    
2. Negative Log-Likelihood
    
3. Margin Classifier
    
4. Soft Margin Classifier
    

* Activation functions decide whether a neuron should be activated or not by calculating a weighted sum and adding bias to it.
    
* The purpose of the activation function is to introduce non-linearity into the output of a neuron.
    
* In a neural network, we would update the weights and biases of the neurons based on the error at the outputs.
    
* This process is known as back-propagation. Activation function makes the back-propagation possible since the gradients are supplied along with the errors to update the weights and biases.