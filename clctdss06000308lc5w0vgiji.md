# #57 Machine Learning & Data Science Challenge 57

# Detailed explanation about gradient descent using examples and Mathematical expression?

**Gradient descent is an optimization algorithm used to minimize some functions by iteratively moving in the direction of the steepest descent as defined by the negative of the gradient.**

* In machine learning, we used gradient descent to update the parameters of our model. Parameters refer to coefficients in the Linear Regression and weights in neural networks.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673544886403/85f9862e-8093-4450-ad0c-69dd0faee021.png align="center")

* The size of these steps is called the learning rate. With the high learning rate, we can cover more ground with each step, but we risk overshooting the lower point since the slope of the hill is constantly changing. With a very lower learning rate, we can confidently move in the direction of the negative gradient because we are recalculating it so frequently.
    
* The Lower learning rate is more precise, but calculating the gradient is time-consuming, so it will take a very large time to get to the bottom.
    

### Math:

* Now let’s run gradient descent using the new cost function. There are two parameters in the cost function we can control: m (weight) and b (bias).
    
* Since we need to consider the impact each one has on the final prediction, we need to use partial derivatives.
    
* We calculate the partial derivative of the cost function concerning each parameter and store the results in a gradient.
    

#### Math Given the cost function:

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673545140447/51f4b5d4-a054-4370-858f-af1803c0be99.png align="center")

* To solve for the gradient, we iterate by our data points using our new m and b values and compute the partial derivatives.
    
* This new gradient tells us about the slope of the cost function at our current position (current parameter values) and the directions we should move to update our parameters. The learning rate controls the size of our update.