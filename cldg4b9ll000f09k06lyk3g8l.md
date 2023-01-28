# #77 Machine Learning & Data Science Challenge 77

# What is RESNET?

**The winner of ILSRVC 2015, also called Residual Neural Network (ResNet) by Kaiming.**

* This architecture introduced a concept called “**skip connections**”.
    
* Typically, the input matrix calculates in two linear transformations with the ReLU activation function. In the Residual network, it directly copies the input matrix to the second transformation output and sums the output in the final ReLU function.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1674920188570/62a5f0f6-1ca1-491e-aac9-3c3dc8b24f17.png align="center")

### Skip Connection

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1674920209697/029a18f4-2e5d-4f90-aca9-c9a0291bbcd1.png align="center")

* Experiments in paper four can judge the power of the residual network. The plain 34-layer network had high validation errors than the 18 layers plain network.
    
* This is where we realize the degradation problems. And the same 34 layers network when converted to the residual network has much less training error than the 18 layers residual network.