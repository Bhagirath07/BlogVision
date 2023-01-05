# #23 Machine Learning & Data Science Challenge 23

# What are F1 Score, Precision, and Recall?

## Recall:-

* Recall can be defined as **the ratio of the total number of correctly classified positive examples divided by the total number of positive models.**
    

1. High Recall indicates the class is correctly recognized (small number of FN).
    
2. Low Recall indicates the class is incorrectly recognized (a large number of FN).
    

* The relation gives recall:
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672657820461/cd1d130f-10b3-40ca-b662-a360cc1203b3.png align="center")

## Precision:

* To get the value of precision, **we divide the total number of correctly classified positive examples by the total number of predicted positive models.**
    

1. High Precision indicates an example labeled as positive is indeed positive (a small number of FP).
    
2. Low Precision indicates an example labeled as positive is indeed positive (large number of FP).
    

* The relation gives precision:
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672657847739/fb788c7a-c7bc-4e66-85b1-059f806c0e71.png align="center")

**Note**:-

* **High recall, low precision: This means that most of the positive examples are correctly recognized (low FN), but there are a lot of false positives.**
    
* **Low recall, high precision: This shows that we miss a lot of positive examples (high FN), but those we predict as positive are indeed positive (low FP).**
    

## **F-measure/F1-Score:**

* Since we have two measures (Precision and Recall), it helps to have a measurement that represents both of them.
    
* We calculate an **F-measure, which uses Harmonic Mean in place of Arithmetic Meaning that it punishes extreme values more.**
    

**The F-Measure will always be nearer to the smaller value of Precision or Recall.**

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1672657893563/679411d7-2873-4803-9751-2abd3c3768a4.png align="center")