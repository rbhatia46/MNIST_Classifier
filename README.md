# MNIST_Classifier
A simple Convolutional neural network that classifies handwritten digits using the MNIST dataset implemented using Keras on a Theano backend

## Instructions to change to a Theano backend

Keras uses tensorflow as a backend choice by default. There is a slight difference between tensorflow and theano in terms of how we input the 
matrix and this code uses a Theano backend so you need to change the backend to Theano.

In your home directory, find the .keras folder inside which you will find keras.json file with the following contents
```
{
    "floatx": "float32",
    "epsilon": 1e-07,
    "image_data_format": "channels_last",
    "backend": "tensorflow"
}
```

Replace 'tensorflow' with 'theano' to successfully use this code to classify handwritten digits.
