# #34 Machine Learning & Data Science Challenge 34

# What is Principal Component Analysis (PCA), and why do we do it?

* **The main idea of principal component analysis (PCA) is to reduce the dimensionality of a data set consisting of many variables correlated with each other, either heavily or lightly, while retaining the variation present in the dataset, up to the maximum extent.**
    
* The same is done by transforming the variables to a new set of variables, which are known as the principal components (or simply, the PCs) and are orthogonal, ordered such that the retention of variation present in the original variables decreases as we move down in the order.
    
* So, in this way, the 1st principal component retains the maximum variation that was present in the original components. The principal components are the eigenvectors of a covariance matrix, and hence they are orthogonal.
    

#### Main important points to be considered:

1. Normalize the data
    
2. Calculate the covariance matrix
    
3. Calculate the eigenvalues and eigenvectors
    
4. Choosing components and forming a feature vector
    
5. Forming Principal Components