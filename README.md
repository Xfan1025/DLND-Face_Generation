# DLND-Face_Generation using DC-GAN

This project is part of Udacity DLND. It is a Deep Convelutional Generative Adversarial Network trained on the CelebA dataset to generate new faces. The network is tested on MNIST dataset to generate digits.

## Architecture

The architecture of DC-GAN contains a generator and a discriminator.

The generator used in the [original paper](https://arxiv.org/pdf/1511.06434.pdf): 
![](https://github.com/Xfan1025/DLND-Face_Generation/blob/master/assets/dcgan.png)

I have reduced the number of units in the generator and reduced the number of layers for discriminator. I was still able to generate quite clear faces. So, if you got more computation power, you should try to make the network deeper to get better result.


## MNIST
I only trained it for 2 epochs. You should get better result if train it longer.

![](https://github.com/Xfan1025/DLND-Face_Generation/blob/master/assets/MNIST.gif)

## CelebA
Trained after 2 epochs.

![](https://github.com/Xfan1025/DLND-Face_Generation/blob/master/assets/CelebA.gif)
