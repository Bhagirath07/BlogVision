# #61 Machine Learning & Data Science Challenge 61

# What is gradient descent, mini-batch gradient descent, batch gradient descent, stochastic gradient descent, and adam?

## Gradient Descent:

**it is an iterative machine learning optimization algorithm to reduce the cost function, and help models make accurate predictions.**

* Gradient indicates the direction of increase. As we want to find the minimum points in the valley, we need to go in the opposite direction of the gradient. We update the parameters in the negative gradient direction to minimize the loss.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673550713358/ded66f95-97f9-498d-86f2-e801619d1f10.png align="center")

* Where θ is the weight parameter, η is the learning rate, and ∇J(θ;x,y) is the gradient of the weight parameter θ.
    

## Types of Gradient Descent:

* Batch Gradient Descent or Vanilla Gradient Descent
    
* Stochastic Gradient Descent
    
* Mini batch Gradient Descent
    

### **Batch Gradient Descent or Vanilla Gradient Descent:**

* **In the batch gradient, we use the entire dataset to compute the gradient of the cost function for each iteration for gradient descent and then update the weights.**
    

### **Stochastic Gradient descent:**

* **In stochastic gradient descent, we use a single data point or example to calculate the gradient and update the weights with every iteration.**
    
* We first need to shuffle the datasets so that we get a completely randomized dataset. As the datasets are random and weights, are updated for every single example, an update of the weights and the cost functions will be noisy jumping all over the place.
    

### **Mini Batch Gradient descent:**

* **Mini-batch gradients are a variation of stochastic gradient descent where instead of a single training example, a mini-batch of samples is used.**
    
* Mini-batch gradient descent is widely used and converges faster and is more stable.
    

The batch size can vary depending on the dataset.

As we take batches with different samples, it reduces the noise which is a variance of the weights updates, and that helps to have a more stable convergence faster.