# Basic-CNN-Implementation

This is a beginner-level implementation of the Convolutional Neural Network or CNN, which is an essential algorithm in image processing.

Here the **CIFAR-100** dataset has been used which includes 60,000 colorful images in total. 50,000 of them are used for the training set and 10,000 are used for the testing set. Each image is 32x32 pixels in size or dimension. Since it is a colorful image, it will have 3 filters corresponding to the 3 channels of RGB.

I have built our CNN model with **5 convolution layers** and **3 max pooling** operations. After it generates a 1x1xN  matrix, I flatten it and feed it into the Fully Connected layer which will classify the images. This is done because the FC layer only takes vector inputs. 

By changing parameters like learning rates, the number of epochs and the number of steps per epoch, we try to improve the accuracy at every test.

Initially, I have done it  7 times and reached an accuracy of 31.9% from 19.7%. 
