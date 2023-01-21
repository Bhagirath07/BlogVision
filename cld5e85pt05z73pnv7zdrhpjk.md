# #63 Machine Learning & Data Science Challenge 63

# What is CNN?

* This is the simple application of a filter to an input that results in inactivation.
    
* Repeated application of the same filter to input results in a map of activations called a feature map, indicating the locations and strength of a detected feature in input, such as an image.
    
* Convolutional layers are the primary building blocks used in convolutional neural networks.
    

A convert is the sequence of layers, and every layer transforms one volume to another through differentiable functions.

## Different types of layers in CNN:

**Let’s take an example by running a comment on of image of dimensions 32 x 32 x 3.**

### **Input Layer:**

* It holds the raw input of the image with width 32, height 32, and depth 3.
    

### **Convolution Layer:**

* It computes the output volume by adding dot products between all filters and image patches. Suppose we use a total of 12 filters for this layer we’ll get an output volume of dimension 32 x 32 x 12.
    

### **Activation Function Layer:**

* This layer will apply the element-wise activation function to the output of the convolution layer. Some activation functions are RELU: max(0, x), Sigmoid: 1/(1+e^-x), Tanh, Leaky RELU, etc. So the volume remains unchanged. Hence output volume will have dimensions 32 x 32 x 12.
    

### **Pool Layer:**

* This layer is periodically inserted within the covnets, and its main function is to reduce the size of volume which makes the computation fast reduces memory, and also prevents overfitting.
    
* Two common types of pooling layers are max pooling and average pooling. If we use a max pool with 2 x 2 filters and stride 2, the resultant volume will be of dimension 16x16x12.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673620706671/8ad32e44-fb91-4f7d-9a98-73207cb50e2b.png align="center")

### **Fully-Connected Layer:**

* This layer is a regular neural network layer that takes input from the previous layer and computes the class scores and outputs the 1-D array of size equal to the number of classes.
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673620734561/e31de8f6-8dfa-4581-bc98-b8bb3a9aa75b.png align="center")