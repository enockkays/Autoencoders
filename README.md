# Autoencoders
An autoencoder is a type of feedforward neural network that attempts to copy its input to its output. Internally, it has a hidden layer, h, that describes a code, used to represent the input. The network consists of two parts:

<ul>
<li>An encoder function: <i>h=f(x)</i>.</li>
<li>A decoder function, that produces a reconstruction: <i>r=g(h)</i>.</li>
  </ul>

The figure below shows the autoencoder architecture. First, the input passes through the encoder, which is a fully-connected neural network, in order to produce the code. The decoder, which has the similar neural network structure, then produces the output by using the code only. The aim is to get an output identical to the input.

![image](https://user-images.githubusercontent.com/32764779/163765049-7f2460a7-ddbc-4908-83f0-3ab2b3aa3f5a.png)

In order to build an autoencoder, three things are needed: an encoding method, a decoding method, and a loss function to compare the output with the target.


# References
1. https://ml-cheatsheet.readthedocs.io/en/latest/architectures.html
2. https://towardsdatascience.com/applied-deep-learning-part-3-autoencoders-1c083af4d798
