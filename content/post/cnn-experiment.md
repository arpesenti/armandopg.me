+++
date = "2016-04-06T16:49:41+01:00"
draft = false
title = "Convolutional Neural Network experiment"
+++

{{< youtube fVVDgSvliiQ >}}

The video shows a little experiment I have been working on in the last days: training a convolutional neural network using [TensorFlow](http://www.tensorflow.org) to "follow" a sidewalk. The output of the classifier are three probabilities that represent if the best option is to continue *forward*, turn *left* or turn *right* (the overlaid green arrow correspond to the highest probability).    
<!--more-->
The dataset is still very small, I have just recorded three 30 seconds videos on three different streets on my neighbourhood (two for training, one for testing). In the above testing video the classifier has a promising 92% accuracy. Still to be evaluated how the performance change with a greater variety of environments.
