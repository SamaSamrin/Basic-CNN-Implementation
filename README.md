# Basic-CNN-Implementation

A beginner-level implementation of the Convolutional Neural Network or CNN, which is an essential algorithm in image processing.

Here the CIFAR-100 dataset has been used which includes 60,000 colorful images in total. 50,000 of them are used for training set and 10,000 are used for testing set. Each image is 32x32 pixels in size or dimension. Since it is a colorful image, it will have 3 filters corresponding to the 3 channels of RGB. 

We have built our CNN model with 5 convolution layers and 3 max pooling operations. After we get a 1x1xN resulting matrix, we flatten it and feed it into the Fully Connected layers. These will classify the images.

By changing parameters like learning rates, number of epoches and number of steps per epoch, we try to improve the accuracy on every testing. 

Initially we have done it only 7 times and reached an accuracy of 31.9% from 19.7%. We will work on this further in the future. 
