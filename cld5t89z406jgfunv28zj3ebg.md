# #64 Machine Learning & Data Science Challenge 64

# What is the pooling operation on CNN?

### Pooling Layer:

* It is commonly used to periodically insert a Pooling layer in-between successive Conv layers in a ConvNet architecture.
    
* Its function is to progressively reduce the spatial size of the representation to reduce the number of parameters and computations in the network and hence also control overfitting.
    
* The Pooling Layer operates independently on every depth slice of the input and resizes it spatially, using the MAX operation.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673621133471/06bb8461-5228-429d-a575-32b09c51df04.png align="center")

* The most common form is a pooling layer with filters of size 2x2 applied with a stride of 2 downsamples of every depth slice in the input by two along both width and height, discarding 75% of the activations.
    
* Every MAX the operation would, in this case, be taking a max over four numbers (little 2x2 region in some depth slice). The depth dimension remains unchanged.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1673621200368/a7bdb0d4-78cd-43f2-ae18-57e6a5d099f5.png align="center")