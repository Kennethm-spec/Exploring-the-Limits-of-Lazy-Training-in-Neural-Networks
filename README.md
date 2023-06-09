## EECS 6699: Final Project, Spring 2023
# Exploring the Limits of Lazy Training in Neural Networks

This is the repository of source code for our Mathematics of Deep Learning project EECS E6699,
by: [Maddie](https://github.com/maddie-kearns), [Sam](https://github.com/sdb2174), and [Kenneth](https://github.com/Kennethm-spec).

This repository contains codes for:

1. Exploring lazy training with a synthetic dataset and a single hidden layer.
2. Exploring lazy training with a synthetic dataset and multiple hidden layers.
3. Exploring lazy training with the MNIST dataset.

<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About](#about-the-project)
* [Training & Performance Evaluation](#training-and-performance-evaluation)
* [Results](#results)

## About The Project

Deep neural networks have revolutionized machine learning and are gaining significant
press for their potential applications on a wide range of tasks. In recent work,
a ‘lazy training’ regime has been documented, in which the weights of a heavily
over-parameterized network do not move significantly during training but remain
close to their random initialization. This allows the network to avoid overfitting
and reduces the heavy computational cost traditionally associated with training deep
neural networks. In this project, we confirm the existence of lazy training through
experiments with random synthetic data and establish a level of significance for
weight movement to classify when the lazy training regime is in effect. This allows
us to determine how over-parameterized a network must be for lazy training to occur.
Furthermore, we explore applying lazy training to networks deeper than one hidden
layer, on both the synthetic data and the MNIST dataset.

## Training And Performance Evaluation

Code for training and performane evaluation of Lazy Training methods synthetic and structured data can be found in following files:

1. Single Layer:  [synthetic_single_layer.ipynb](src/pytorch_code/synthetic_single_layer.ipynb)
2. Two Layer: [two_layer.ipynb](src/tensorflow_code/two_layer.ipynb)
3. Three Layer: [three_layer.ipynb](src/tensorflow_code/three_layer.ipynb)
4. Sample Loss: [sample_loss.ipynb](src/tensorflow_code/sample_loss.ipynb)

## Results
A final evaluation is concluded in our report:

* [Exploring Lazy Training in Deep Feedforward Neural Networks](Mathematics_of_Deep_Learning_Project_Report.pdf)
