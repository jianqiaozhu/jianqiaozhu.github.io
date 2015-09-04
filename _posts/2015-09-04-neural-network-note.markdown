---
layout: post
comments: false
title:  "Some Crucial Facts about Neural Networks"
excerpt: "We'll approach these facts through a simple and visualized way  rather than going deep in math."
date:   2015-09-04 13:14:00
mathjax: true
---


**The Universality Theorem**

Put the theoream in one line:

> Neural networks with a single hidden layer can be used to approximate any continuous function to any desired precision.

That said, the exciting property of neural networks is the ability to mimick any function. You can find a good introduction from [Michael Nielson's book](http://neuralnetworksanddeeplearning.com/chap5.html)


**The Hierarchies of Knowledge**

Real-world problems often describe in complex concepts and need to be solved hierarchically. Take computer vision for example, to train a system to make sense of individual pixels and edges is a simple task, but difficult to identify geometric shapes and multi-object scenes. This is where deep networks came in.

> Complex concepts can be solved in deep networks where hierarchical structures were adapted to learn the hierarchies of knowledge


However, just because something is possible doesn't make it a good idea. Intuitively, deeper networks should become increasingly hard to train. Thus far, we know that the [stochastic gradient descent (SGD)](https://en.wikipedia.org/wiki/Stochastic_gradient_descent) learning algorithm will run into trouble when training deep networks.










