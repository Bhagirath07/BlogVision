# #69 Machine Learning & Data Science Challenge 69

# What is the batch size?

### Batch Size:

**The total number of training and examples present in a single batch.**

* Unlike the learning rate hyperparameter where its value doesn’t affect computational time, the batch sizes must be examined in conjunction with the execution time of training.
    
* The batch size is limited by the hardware’s memory, while the learning rate is not.
    
* Leslie recommends using a batch size that fits in the hardware’s memory and enables using a larger learning rate.
    
* If our server has multiple GPUs, the total batch size is the batch size on a GPU multiplied by the number of GPUs.
    
* If the architectures are small or your hardware permits very large batch sizes, then you might compare the performance of different batch sizes. Also, recall that small batch sizes add regularization while large batch sizes add less, so utilize this while balancing the proper amount of regularization.
    
* It is often better to use large batch sizes so a larger learning rate can be used.