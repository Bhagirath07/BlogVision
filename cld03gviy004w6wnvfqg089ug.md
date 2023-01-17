# #56 Machine Learning & Data Science Challenge 56

# List down all the activation functions using mathematical Expressions and examples. What is the activation function?

**Activation functions are very important for an Artificial Neural Network to learn and make sense of something complicated and the Non-linear complex functional mappings between the inputs and response variable.**

* They introduce non-linear properties to our Network. Their main purposes are to convert an input signal of a node in an A-NN to an output signal.
    

#### So why do we need Non-Linearities?

**Non-linear functions are those, which have a degree of more than one, and they have a curvature when we plot a Non-Linear function.**

* Now we need a Neural Network Model to learn and represent almost anything and any arbitrary complex function, which maps inputs to outputs.
    
* Neural-Networks are considered Universal Function Approximations. It means that they can compute and learn any function at all.
    

Most popular types of Activation functions:

1. Sigmoid or Logistic
    
2. Tanh - Hyperbolic Tangent
    
3. ReLu - Rectified Linear Units
    

### Sigmoid Activation function:

* It is an activation function of form f(x) = 1 / 1 + exp(-x). Its Range is between 0 and 1. It is an S-shaped curve. It is easy to understand
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673536460495/5793fcdb-7cea-4f8b-9846-263eddb5a315.png align="center")

### Hyperbolic Tangent function- Tanh:

* It’s mathematical formula is f(x) = 1 exp(-2x) / 1 + exp(-2x). Now it’s the output is zero-centered because its range is between -1 to 1 i.e. -1 &lt; output &lt; 1. Hence optimization is easier in this method; Hence in practice, it is always preferred over the Sigmoid function.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673536479509/1a86484c-c531-442c-a0f4-4bbd8cd004d2.png align="center")

### ReLu- Rectified Linear units:

* It has become more popular in the past couple of years. It was recently proved that it has a six times improvement in convergence from the Tanh function. It’s R(x) = max (0,x) i.e. if x &lt; 0 , R(x) = 0 and if x &gt;= 0 , R(x) = x.
    
* Hence as seen in the mathematical form of this function, we can see that it is very simple and efficient. Many times in Machine learning and computer science we notice that the most simple and consistent techniques and methods are only preferred and are the best.
    
* Hence, it avoids and rectifies the vanishing gradient problem. Almost all the deep learning Models use ReLu nowadays.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673536492634/a0e7b3f2-db58-4005-9412-1ea5403736ac.png align="center")