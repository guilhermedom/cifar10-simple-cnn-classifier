# Classifying CIFAR-10 Images Using a Simple CNN

Simple TensorFlow [Convolutional Neural Network] (CNN) classifier with 4 convolutional and 3 fully connected layers working on the [CIFAR-10] dataset.

![proposed_model_architecture](https://user-images.githubusercontent.com/33037020/188351488-ec1d6e2e-33b7-4500-80d3-411a2f4d1e80.png)

---

## Problem Overview

CIFAR-10 is an image dataset having 60000 images divided into 10 different classes, which may be animals or objects nouns. Many different techniques and architectures have been proved to achieve great results on this dataset. 

However, results from such networks may be too difficult to interpret or may depend too much on data preprocessing. Additionally, some may not want to preprocess CIFAR-10's images before training a model. The reason for this is that preprocessing may transform the original dataset into a new one.

## Analysis Introduction

In this notebook, we show that it is possible to use a simple CNN to achieve reasonable results, better than some of the first published results on CIFAR-10 (e.g., McDonnell, Mark D., and Tony Vladusich. "Enhanced image classification with a fast-learning shallow convolutional neural network." 2015 International Joint Conference on Neural Networks (IJCNN). IEEE, 2015.).

Below we can see a random collection of CIFAR-10 images, labeled with their actual classes and their predicted classes, according to our CNN model:

![cifar10-simple-cnn-classifier](https://user-images.githubusercontent.com/33037020/188351002-543d42d9-194b-44d0-8710-fb6091502804.png)

The model's accuracy is measured at 78% for the testing set. The obtained confusion matrix using the model predictions also backs up our conclusion: a simple CNN can be handily used in simple image classification tasks. 

![cifar10-simple-cnn-classifier2](https://user-images.githubusercontent.com/33037020/188351005-428f1934-3892-4c53-8519-214dc14a266e.png)

[//]: #

[Convolutional Neural Network]: <https://insightsimaging.springeropen.com/articles/10.1007/s13244-018-0639-9>
[CIFAR-10]: <https://www.cs.toronto.edu/~kriz/cifar.html>
