# Handwritten-digit-recognition-MNIST
Handwritten Digit Recognition using Convolutional Neural Networks in Python with Keras

## MNIST dataset:

MNIST is a collection of handwritten digits from 0-9. 
Image of size 28 X 28

![alt text](https://github.com/shubham99bisht/Handwritten-digit-recognition-MNIST/blob/master/src/mnist-sample.png "MNIST")

## Code Requirements
python 3.x with following modules installed

1. numpy
2. seaborn
3. tensorflow
4. keras
5. opencv2

## Description
This is a 5 layers Sequential Convolutional Neural Network for digits recognition trained on MNIST dataset. I choosed to build it with keras API (Tensorflow backend) which is very intuitive. 

It achieved 98.51% of accuracy with this CNN trained on a GPU, which took me about a minute. If you dont have a GPU powered machine it might take a little longer, you can try reducing the epochs (steps) to reduce computation.

## Execution

![alt text](https://github.com/shubham99bisht/Handwritten-digit-recognition-MNIST/blob/master/src/ml2.gif)

To run the code type, 

`python digit_recogniser.py`


## Tutorial
**Note: This page is not complete. Will be updated soon! sorry for delay.**

For step-by-step tutorial please refer to [wiki](https://github.com/shubham99bisht/Handwritten-digit-recognition-MNIST/wiki). It will take you through all the steps right from loading the data to recognising digits through live cam.
