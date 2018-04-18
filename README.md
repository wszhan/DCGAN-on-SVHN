# DCGAN-on-SVHN

![SVHN Sample](http://ufldl.stanford.edu/housenumbers/32x32eg.png)

A deep convolutional generative adversarial neural network implementation. In this project, we will mostly focus on the generative part rather than the discriminative part, that means we want to generate new 'fake' images that highly resemble the original SVHN data. Statistically, we want the 'fake' data distribution be as close as possible to the 'real' SVHN data distribution. Visually, the output images from the generator would look similar to the SVHN data, though to human eyes the differences can still be told.

This project is based on [the original paper](https://arxiv.org/pdf/1511.06434.pdf).

The data is trained on the [The Street View House Numbers (SVHN) Dataset](http://ufldl.stanford.edu/housenumbers/).

The project is trained on AWS Ubuntu EC2 Instance with GPU. Training on CPU is not recommended.

Setting a working environment on AWS might be not difficult but pretty erroneous. I have written posts about the possible problems while training the model and on how to set up Anaconda on AWS(if you are using Anaconda version of TensorFlow-GPU). On my blog there are more posts on AWS and Neural Network.
