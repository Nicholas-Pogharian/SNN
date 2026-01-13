# SNN

## Project Description

This repository contains Python code with classes and functions for constructing and testing a spiking neural network. The spiking neural network is composed of two classes: an InhibitedNeuronLayer and a SynapseLayer, acting as the neurons and synaptic connections in the network respectively. Benchmarking of the network for unsupervised learning is done using the MNIST database of handwritten digits.

---
## Introduction to Spiking Neural Networks


---
## Results


---
## Instructions

This code was written using Python 3.9.7. It requires the numpy (version 1.22.4 or better) and scikit-learn (version 1.6.1 or better) packages. Run in the command line. There are 8 command line arguments: 
1. The number of neurons in the output layer of the network
2. $\theta$ value for neurons in the network
3. Presentation time for each digit
4. Duration of each spike
5. Potentiation learning rate $\alpha_p$
6. Depression learning rate $\alpha_d$
7. Potentiation nonlinearity term $\beta_p$
8. Depression nonlinearity term $\beta_d$
