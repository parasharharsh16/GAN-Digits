# GAN-Digits
This repository contains code for training a Generative Adversarial Network (GAN) to generate digit images using TensorFlow. The GAN model is trained on the MNIST digits dataset. Various combinations of hyperparameters have been explored, including different numbers of epochs and batch sizes. The final architecture of the generator model has been modified and fine-tuned to achieve the best performance.

###Generator Architecture
The final architecture of the generator model consists of several layers including dense layers, batch normalization, leaky ReLU activations, and Conv2DTranspose layers. Each layer is carefully designed to transform random noise into realistic digit images.

###Experimentation
Throughout the development process, various experiments have been conducted by adjusting hyperparameters such as learning rate, batch size, and network architecture. Different combinations of these parameters have been tested to find the optimal configuration for training the GAN model on the MNIST dataset.

###Conclusion
The final implementation represents the culmination of these experiments, resulting in a GAN model capable of generating realistic digit images. By leveraging TensorFlow and carefully tuning the architecture and hyperparameters, this project demonstrates the power of deep learning in generating synthetic data.
