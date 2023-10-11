# mask-detection
In this project, we have developed a deep learning model for face mask detection using Python, Keras, and OpenCV. We developed the face mask detector model for detecting whether person is wearing a mask or not. We have trained the model using Keras with network architecture. preprocessing the model is the first part of this project ,training the model is the second part and testing using webcam using OpenCV is the third part.


Data preprocessing:
Loading the data set.printed it's categories.created two arrays data and target 

Data training:
Importing the required packages from respective libraries.

Build the neural network:
This convolution network consists of two pairs of Conv and MaxPool layers to extract features from the dataset. Which is then followed by a Flatten and Dropout layer to convert the data in 1D and ensure overfitting.And then two Dense layers for classification.
