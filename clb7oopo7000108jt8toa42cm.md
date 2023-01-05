# #8 Machine Learning & Data Science Challenge 8

# Why Support Vector Regression? Difference between SVR and a simple regression model?

*   In simple regression, try to minimize the error rate. But in SVR, we try to fit the error within a certain threshold.
    

## Concepts:

1.  **Boundary**
    
2.  **Kernel**
    
3.  **Support Vector**
    
4.  **Hyper Plane**
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1669993238171/16d4c3cc-6e83-40ad-8608-3963ccbf5340.png align="center")
![Blue line: Hyper Plane; Red line: Boundary-Line](https://cdn.hashnode.com/res/hashnode/image/upload/v1669993253406/f8ac3f51-bdcf-4153-9c1f-47954a017bc9.png align="center")

*   Our best fit line is the one where **the hyperplane has the maximum number of points.**
    
*   We are trying to do here is trying to decide on a decision boundary at `e` **distance from the original hyperplane such that data points closest to the hyperplane** or **the support vectors are within that boundary line.**
    

![](https://cdn.hashnode.com/res/hashnode/image/upload/v1669993622993/c1e7de94-cc31-4d8a-b4ed-b39477f4b7c2.png align="center")