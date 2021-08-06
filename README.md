# Convolutional-Autoencoders
Example on the use of Convolutional autoencoders on the MNIST and Fashion-MNIST datasets.

Autoencoder neural networks are typically used to reconstruct input object. The scheleton concept of the architecture consists of an encoder, which layers serve the purpose of compacting the input information in less dimensions, followed by a decoder, which uses such reduced information to reconstruct the input object. The training is done in such a way that the network is penalized by the difference of the reconstruction with respect to the input object. 

When dealing with images, one of the use of Autoencoder architecture is outlier detection. If we train a network to reconstruct a certain types of images, the network will perform worse if it were to reconstruct other types of images. 

In this repository we implement an autoencoder to reconstruct MNIST images (handwritten digits), and see its performance on Fashion-MNIST images (Zalando images). 


