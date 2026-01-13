# SNN

## Project Description

This repository contains Python code with classes and functions for constructing and testing a spiking neural network. The spiking neural network is composed of two classes: an InhibitedNeuronLayer and a SynapseLayer, acting as the neurons and synaptic connections in the network respectively. Benchmarking of the network for unsupervised learning is done using the MNIST database of handwritten digits.

---
## Introduction to Spiking Neural Networks


---
## Results
Using 200 output neurons, $\theta=1$, $\alpha_p=0.001$, $\alpha_d=-0.0005$, $\beta_p=\beta_d=3$, the network was trained for 10 epochs. Each digit was presented for 350 ms, and each spike lasted 25 ms. The resulting confusion matrix is displayed below.
![Alt text](figures/confusion_matrix.png)

---
## Instructions

This code was written using Python 3.9.7. It requires the numpy (version 1.22.4 or better) and scikit-learn (version 1.6.1 or better) packages. To train the network, test the network on out-of-sample data, and print results including a confusion matrix for digit recognition, run 'SNN.py' in the command line. There are 8 command line arguments denoting hyperparameters of the network: 
1. The number of neurons in the output layer of the network
2. $\theta$ value for neurons in the network
3. Presentation time for each digit
4. Duration of each spike
5. Potentiation learning rate $\alpha_p$
6. Depression learning rate $\alpha_d$
7. Potentiation nonlinearity term $\beta_p$
8. Depression nonlinearity term $\beta_d$
Additionally, the number of training epochs can be tuned via the 'train_epochs' function in 'SNN.py'.
