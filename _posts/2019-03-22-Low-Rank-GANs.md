---
title: "Low Rank Approximation of Weight Matrices in GANs"
layout: post
date: 2019-03-22 1:13
image: /assets/images/markdown.jpg
headerImage: false
tag:
    - GANs
category: blog
author: arnavgarg
description: Low Rank Approximation of Weight Matrices in GANs
---

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-MML-AM_CHTML">
</script>

# Abstract

Generative Adversarial Networks are hard to train and several recent works have focused on improved regularization by controlling the spectra of weight matrices. Most recently, Jiang et. al proposed a new reparameterization technique in his paper "On computationand generalization of generative adversarial networks under spectrum control" which learns the Singular Value Decomposition of each weight matrix in the network - thus, allowing us to directly manipulate the spectra of the matrices. Our work builds on this existing body of literature by introducing a generalized method for training neural networks using this reparameterization and reducing the number of parameters by restricting the rank of each weight matrix. For a GAN, we find a theoretical upper bound on the distance between the original discriminator and its k-rank approximation along with good results on the CIFAR-10 dataset by using matrices with restricted rank. Furthermore, we demonstrate high accuracy on the MNIST dataset by using low rank weight matrices and show a significant decrease in the number of parameters required as compared to a network composed of traditional convolutional layers.


You can read more here: [LINK](../assets/papers/gans.pdf)

Code: [LINK](https://github.com/thearnavgarg/GAN-Stabilization)