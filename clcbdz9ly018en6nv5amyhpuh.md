# #17 Machine Learning & Data Science Challenge 17

# What is SVM Classification?

* **SVM or Large margin classifier is a supervised learning algorithm that uses a powerful technique called SVM for classification.**
    
* We have two types of SVM classifiers:
    

### Linear SVM:

* In Linear SVM, the data points are expected to be separated by some apparent gap. Therefore, the SVM algorithm predicts a straight hyperplane dividing the two classes.
    
* The hyperplane is also called a **maximum margin hyperplane.**
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672394669557/cad7b552-7bc8-4db3-9ddc-3a6bab696fc9.png align="center")

### Non-Linear SVM:

* It is possible that our data points are non-linearly separable in a p-dimensional space, but can be linearly separable in a higher dimension.
    
* Kernal tricks make it possible to draw nonlinear hyperplanes.
    
* Some standard kernels are;
    
    1. **Polynomial Kernel**
        
    2. **RBF Kernel**
        

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672395130468/ac9b2f83-492e-493d-8f91-7eb4563a270f.png align="center")

### Advantages of SVM classifier:

1. SVMs are effective when the number of features is quite large.
    
2. It works effectively even if the number of features is greater than the number of samples.
    
3. Non-Linear data can also be classified using customized hyperplanes built by using kernel trick.
    
4. It is a robust model to solve prediction problems since it maximizes margin.
    

### Disadvantages of SVM classifier:

1. The biggest limitation of the Support Vector Machine is the choice of the kernel. The wrong choice of the kernel can lead to an increase in error percentage.
    
2. With a greater number of samples, it starts giving poor performances.
    
3. SVMs have good generalization performance, but they can be extremely slow in the test phase.
    
4. SVMs have high algorithmic complexity and extensive memory requirements due to the use of quadratic programming.