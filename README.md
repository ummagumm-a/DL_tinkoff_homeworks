# Homework 1
1) Classification of Handwritten digits (MNIST dataset). I used linear layers, then convolutional layers, tried VGG-like pattern.
2) Morphing between two letters implemented using autoencoder.

https://user-images.githubusercontent.com/70323559/157639196-c7b1593a-8f35-407b-8ebb-df6b16e4a393.mp4

3) Visualization of digits in latent space
![mnist_vis](https://user-images.githubusercontent.com/70323559/157639247-f91c7f50-845e-4a6a-ae5d-02c7e4eed4c8.jpg)

# Homework 3
A small network written in python using numpy.

The framework logic is in *hw_framework.ipynb*, testing is in *hw_backprop.ipynb*.

Testing was done on MNIST digits dataset, where I achieved 98% accuracy.

Following layers are implemented:
* Linear
* BatchNorm
* Dropout
* Softmax
* ReLU
* LeakyReLU
* Sigmoid

Criterions:
* MSE
* CrossEntropy

Optimizers:
* SGD
* SGD with Momentum
* AdaGrad
* RMSProp
* AdaDelta
* Adam

Schedulers:
* Linear Decay
* Factor Decay
* MultiFactor Decay
