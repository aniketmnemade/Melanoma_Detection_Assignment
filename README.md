# Melanoma_Detection_Assignment

> **Learning**: Multiclass classification model using a custom convolutional neural network in TensorFlow. 

# Problem statement: 
To build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.


## Table of Contents
* [General Info](#general-information)
The data set contains the following 9 diseases:

 -Actinic keratosis
 -Basal cell carcinoma
 -Dermatofibroma
 -Melanoma
 -Nevus
 -Pigmented benign keratosis
 -Seborrheic keratosis
 -Squamous cell carcinoma
 -Vascular lesion

* [Technologies Used](#technologies-used)
 -Pandas
 -Tensorflow.keras
 -ImageDataGenerator
 -Matplotlib and NumPy:
 -Adam Optimizer
 -ReduceLROnPlateau Callback
* [Conclusions](#conclusions)

* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
Build a CNN based model which can accurately detect melanoma. Melanoma is a type of cancer that can be deadly if not detected early. It accounts for 75% of skin cancer deaths. A solution that can evaluate images and alert dermatologists about the presence of melanoma has the potential to reduce a lot of manual effort needed in diagnosis.
Data set provided with 9 different classes for learning.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Conclusions
Without the ImageDataGenerator model gets to overfit at higher ratio

Rebalance class is reducing overfititng of the data and thus the loss is beng reduced, but it reduced the Acurracy as well

By using dropout and ImageDataGenerator we tried to reduce the overfiting

After that we try to use Batch Normalization with Augumentation to get the outputs.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Version
- Matplotlib - version 3.8.0
- Numpy - version 1.26.4
- Pandas - version 2.1.4
- Seaborn - version 0.13.2
- Sklearn - version 1.2.2
- statsmodels.api - version 0.14.0


## Acknowledgements
Give credit here.
- This project was based on [upGrad].


## Contact
Created by [aniketnagpur@gmail.com] - feel free to contact me!
