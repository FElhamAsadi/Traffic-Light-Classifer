# Project Overview
In this project, we’ll use our knowledge of computer vision techniques to build a classifier for images of traffic lights! We have been given a dataset of traffic light images in which one of three lights is illuminated: red, yellow, or green.

# Classification Steps
In the provided notebook, I've pre-processed these images, extracted features that help distinguish the different types of images, and used those features to classify the traffic light images into three categories: red, yellow, or green. The tasks have been broken down into a few sections:

1. Loading and visualizing the data. The first step in any classification task is to be familiar with the data by loading  the images of traffic lights and visualizing them!

2. Pre-processing. The input images and output labels need to be standardized; that is, all the input should be of the same type of data and of the same size, and the output should be a numerical label. This way, we can analyze all the input images using the same procedures, and we know what output to expect when we eventually classify a new image.

3. Feature extraction. Next, I've extracted some features from each image that are used to distinguish and classify these images. Features should be 1D vectors or even single values that provide some information about an image that can help classify it as a red, yellow, or green traffic light.

4. Classification and visualizing error. Finally, I've written one function that uses our features to classify any traffic light image. This function takes in an image and output a label. I've also used a piece of code to classify a test set of data, compare your predicted label with the true label, and determine the accuracy of my classification model.

