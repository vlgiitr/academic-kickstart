---
# Documentation: https://sourcethemes.com/academic/docs/managing-content/

title: "Layer Level Loss Optimisation"
subtitle: ""
summary: "Experiment to test a method to train neural networks inspired by the Forward-Forward Algorithm "
tags: []
categories: []
date: "2023-10-9T00:00:00Z"

#url_code: "https://github.com/vlgiitr/Sensorium-2022"
url_pdf: ""
url_slides: ""
url_video: ""
projects: []
---
An experiment in testing a novel method to train neural networks inspired by the Forward-Forward Algorithm proposed by Geoffrey Hinton by updating weights of a layer by calculating the loss at each intermediate layer instead of backpropagating the losses
through the entire network.

In the original paper, instead of relying on the traditional forward and backward passes of backpropagation, the method utilized two forward passes — one with positive, real data and the other with negative data.
With our modified method we were able to achieve an error rate of less than 2% for a fully connected network and convolutional network on the MNIST dataset.
