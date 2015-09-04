---
layout: post
comments: false
title:  "Pattern Recognition and Cognitive Models of Risky Choices"
excerpt: "We'll extract features from traditional representation of risky choices and then train a feature-based classifier that learn to predict human risky choices."
date:   2015-09-02 11:35:00
mathjax: true
---

## Why should we care about risky choice?

People make choices everyday and every choice contains different degrees of uncertainty.
That is, we want to make wise decisions when future information is (partly) unknown.
Economists like to describe such choice as playing a gamble between lotteries.
Most likely a lottery is expressed in the form of outcome-probability.
This methodology was also distilled to psychologists.
Say, a lottery, which has two possible outcomes *H, L* and their corresponding probabilities *pH, 1-pH*, can be expressed as follows: $$ (H, pH; L, 1-pH) $$


## What are the existing models like?

I find tournaments great platforms to assess models.
Hence, I have participated in the [Technion's Choice Prediction Competition 2015](http://departments.agri.huji.ac.il/economics/teachers/ert_eyal/rules.htm) (Hereafter, CPC2015).
The primary objective of the tournament is to generate the lowest mean-squared deviation of the test set, which is not available to all participants until they submitted models.
That said, competing models can only be trained by the estimation set.

The winner of CPC2015 (the BEAST model) is an ensemble of many leading cognitive models.
Basically, the BEAST contains [*Expected Value Model*](https://en.wikipedia.org/wiki/Expected_value), *Temporal-difference Learning*, *Attention-weight Model*, and *Priority Heuristic Model*





