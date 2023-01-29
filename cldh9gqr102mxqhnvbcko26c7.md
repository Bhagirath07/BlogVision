# #80 Machine Learning & Data Science Challenge 80

# What is YOLO and explain the architecture of YOLO (You Only Look Once)? One use case?

## YOLO v1:

* The first YOLO You only look once (YOLO) version came about in May 2016 and sets the core of the algorithm, the following versions are improvements that fix some drawbacks.
    
* In short, YOLO is a network “inspired by” Google Net. It has 24 convolutional layers working as feature extractors and two dense layers for making predictions.
    
* The architecture works upon is called Darknet, a neural network framework created by the first author of the YOLO paper.
    

### Core Concept:

* The algorithm works by dividing the image into the grid of the cells, for each cell bounding box, and their scores are predicted, alongside class probabilities.
    
* The confidence is given in terms of the IOU (intersection over union), metric, which is measuring how much the detected object overlaps with the ground truth as a fraction of the total area spanned by the two together (the union).
    

## YOLO v2:

* This improves on some of the shortcomings of the first version, namely the fact that it is not very good at detecting objects that are very near and tends to make some mistakes in localization.
    
* It introduces a few newer things: Which are anchor boxes (pre-determined sets of boxes such that the network moves from predicting the bounding boxes to predicting the offsets from these) and the use of features that are more fine-grained so smaller objects can be predicted better.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1674925394837/858e83f3-c609-4291-939e-eae841d52fd2.png align="center")

## YOLO v3:

* YOLOv3 came about in April 2018, and it adds small improvements, including the fact that bounding boxes get predicted at different scales.
    
* The underlying meaty part of the YOLO network, Darknet, is expanded in this version to have 53 convolutional layers.
    

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1674925413071/23077e61-2e00-4da7-8035-6f3db4d8456a.png align="center")

> ![](https://cdn.hashnode.com/res/hashnode/image/upload/v1674925432657/a173cc87-8bdb-42ca-8dd3-5511bb8f7ac3.png align="center")