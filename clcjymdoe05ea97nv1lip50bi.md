# #32 Machine Learning & Data Science Challenge 32

# What is KNN Classifier?

* KNN means K-Nearest Neighbour Algorithm. It can be used for both classification and regression.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672816185572/04473359-e027-4aa6-8293-29c930c35fbe.png align="center")

* **It is the simplest machine learning algorithm. Also known as lazy learning.**
    
* (why? Because it does not create a generalized model during the time of training, the testing phase is very important when it does the actual job. Hence Testing is very costly - in terms of time & money).
    
* Also called i**nstance-based or memory-based learning.**
    
* In k-NN classification, **the output is a class membership.**
    
* An object is classified by a plurality vote of its neighbors, with the object being assigned to the class most common among its k nearest neighbors (k is a positive integer, typically small).
    
* If k = 1, then the object is assigned to **the class of that single nearest neighbor.**
    
* **In k-NN regression, the output is the property value for the object. This value is the average of the values of k-nearest neighbors.**
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672816239529/f05af8fb-40a7-4829-a547-862e53659925.png align="center")

* All three distance measures are only valid for continuous variables. In the instance of categorical variables, the Hamming distance must be used.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672816256849/4f50a3ff-2974-48d0-b7ae-babfebc44abe.png align="center")

#### **How to choose the value of K:**

* K value is a hyperparameter that needs to choose during the time of model building.
    
* Also, a small number of neighbors are the most flexible fit, which will have a low bias, but the high variance and a large number of neighbors will have a smoother decision boundary, which means lower variance but higher bias.
    
* We should choose an odd number if the number of classes is even. It is said the most common values are to be 3 & 5.