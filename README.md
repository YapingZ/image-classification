# Content
Identifying MNIST handwritten data sets with CNN.
# Installation
Python 3.5.2
Tensorflow 1.2.1
# Introduction
Identifying handwritten digital pictures using CNN.

The network structure consists of two convolution layers and one fully connected layer and one softmax layer.

Use the ADAM optimizer to do gradient descent.

Use dropout to prevent neural network overfitting.
# Main function
tf.truncated_normal (shape, stddev=0.1)

tf.nn.conv2d ( input, filter, strides, padding )

tf.nn.max_pool(value, ksize, strides, padding,)

tf.nn.dropout(x, keep_prob,)
# Dataset
I’m useing the MNIST Dataset.Each image in the dataset contains 28X28 pixels.

# Train
Create an interactive session.
Train the images in the dataset in batches and cycle through multiple times.
