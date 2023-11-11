# PINNs_Power_System_Dynamics

This repository contains source code necessary to reproduce the results presented in the following paper:

By Huynh T. T. Tran and Hieu T. Nguyen

Accepted to The 2024 Conference on Innovative Smart Grid Technologies, North America (ISGT NA 2024).

The method shown in this repository can be used for modeling the power system dynamics by PINNs.

## Abstract:
In recent years, scientific machine learning, particularly physic-informed neural networks (PINNs), has introduced new innovative methods to understanding the differential equations that describe power system dynamics, providing a more efficient alternative to traditional methods. However, using a single neural network to capture patterns of all variables requires a large enough size of networks, leading to a long time of training and still high computational costs. In this paper, we utilize the interfacing of PINNs with symbolic techniques to construct multiple single-output neural networks by taking the loss function apart and integrating it over the relevant domain. Also, we reweigh the factors of the components in the loss function to improve the performance of the network for instability systems.
Our results show that the symbolic PINNs provide higher accuracy with significantly fewer parameters and faster training time. By using the adaptive weight method, the symbolic PINNs can avoid the vanishing gradient problem and numerical instability.

## Several Numerical Results:

![phase-portrait_symbolic_transform1](https://github.com/ThanhEthan/PINNs_Power_System_Dynamics/assets/115194407/7fa89329-6264-477d-96ab-4d2043e44968)
