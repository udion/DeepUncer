# DeepUncer
This is a set of experiments demonstrating different ways to encorporate uncertainty measurements in a deep neural network.

## Classification settings
Here I used the method described in  [https://arxiv.org/pdf/1703.04977.pdf](https://arxiv.org/pdf/1703.04977.pdf)

## Regression settings
Here I have put priors on inner weights of the conv/linear layers and learnt the parameters of the priors using VI. This uses PYRO framework.


