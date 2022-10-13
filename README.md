# Code for the paper "What does a deep neural network confidently perceive? The effective dimension of high certainty class manifolds and their low confidence boundaries" (https://arxiv.org/abs/2210.05546)
The paper is here: https://arxiv.org/abs/2210.05546
The Colab is here: https://github.com/stanislavfort/slice-dice-optimize/blob/main/cutting_planes_in_JAX.ipynb

The Colab here demonstrates the core experiment of the paper What does a deep neural network confidently perceive? The effective dimension of high certainty class manifolds and their low confidence boundaries. It trains a model from scratch for a few epochs, conducts input space partitioning experiments using random hyperplanes, and caltculates the effective dimension 
 for the class manifolds for each of the CIFAR-10 classes.

The notebook will train a ResNet20v1 on CIFAR-10 for a few epochs and perform our core cutting plane experiment for each single class manifold using a sweep of cutting plane dimensions , each repeated 5 times. You should be able to run this from scratch on a free Google Colab GPU in less than 5 minutes.

The resulting figure will look like this:

<img src="https://github.com/stanislavfort/slice-dice-optimize/blob/main/basic_experiment.ong.png?raw=true" ALIGN="center" height="100%" width="100%">
