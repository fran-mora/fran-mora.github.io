---
layout: post
title: Deep Learning Practical Tips
categories: [Machine Learning]
---

_This is a list of ideas, intuitions and maybe best practices that become useful for applied deep learning._

(Work in Progress)

## Architecture
### Choice of activation functions

| **Layer** | **Activation Function** |
|---|---|
| Dense | ReLU |
| Dense -- final layer for multiclass | softmax |
| Dense -- final layer binary classification | sigmoid |
| Dense -- final layer for regression | linear |
| RNN | tanh |
| Convolutional | LeakyReLU |

