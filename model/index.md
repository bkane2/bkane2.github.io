---
layout: page
title: Model
excerpt: "Details on our NLI model."
search_omit: true
---

## Model architecture

![model architecture](/assets/images/model.png)

## Experiment

#### Train 3 models

* MegaNegRaising

* MegaVeridicality

* Both combined

#### Isotonic regression

* Four-fold cross validation on pilot data

* Fit isotonic regression to calibrate model predictions

#### Other details

* BlueHive cluster of Intel Xeon CPUs

* 10 epochs of training

* MSE loss, Adam optimizer, batch size of 1

* Dropout