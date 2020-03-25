---
title: "The linear representation of CNN for single image"
collection: publications
permalink: /publication/2016-10-icml-linear
date: 2016-10-01
venue: "ICML 2016 Workshop on Visualization for Deep Learning"
citation: 'W Yu, K Yang, Y Bai, <b>T Xiao</b>, H Yao, Y Rui. <i>In ICML 2016 Workshop on Visualization for Deep Learning</i>'
---

[Download paper here](https://icmlviz.github.io/icmlviz2016/assets/papers/14.pdf)


## Abstract
CNN can model the complex underline mappings between images and categories through several layers via non-linear activation function. However, it is hard to analyze the non-linear relation learned in the CNN. In this paper, we show that a set of well-performed CNNs (composed of convolutional layers, max-pooling layers and ReLU) are piecewise linear, i.e., linear at every single image. The nice property means that the output/score of a neuron is a linear combination of outputs of any lower layer for an image. With the property, we can distribute the score of a neuron to every position of a lower layer to probe where contributes more for the score of the neuron.
