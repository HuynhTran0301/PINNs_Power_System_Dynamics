# PINNs_Power_System_Dynamics

This repository contains the source code necessary to reproduce the results presented in the following paper:

Modeling Power Systems Dynamics with Symbolic Physics-Informed Neural Networks.

By Huynh T. T. Tran and Hieu T. Nguyen

Accepted to The 2024 Conference on Innovative Smart Grid Technologies, North America (ISGT NA 2024).

The method shown in this repository can be used for modeling the power system dynamics by PINNs.

## Abstract:
In recent years, scientific machine learning, particularly physic-informed neural networks (PINNs), has introduced new innovative methods to understanding the differential equations that describe power system dynamics, providing a more efficient alternative to traditional methods. However, using a single neural network to capture patterns of all variables requires a large enough size of networks, leading to a long time of training and still high computational costs. In this paper, we utilize the interfacing of PINNs with symbolic techniques to construct multiple single-output neural networks by taking the loss function apart and integrating it over the relevant domain. Also, we reweigh the factors of the components in the loss function to improve the performance of the network for instability systems.
Our results show that the symbolic PINNs provide higher accuracy with significantly fewer parameters and faster training time. By using the adaptive weight method, the symbolic PINNs can avoid the vanishing gradient problem and numerical instability.

## Numerical Results:
### Case study with $\delta = 1$rad and $\omega = -5%rad/s:
![Case 1](https://github.com/ThanhEthan/PINNs_Power_System_Dynamics/assets/115194407/2af034e1-2328-4db3-97db-3511cf13be8b)


### Case study 2 with $\delta = 1$rad and $\omega = -5%rad/s:
![case 2](https://github.com/ThanhEthan/PINNs_Power_System_Dynamics/assets/115194407/3ef98cc5-6cd2-44ed-bae3-46e9cd9fa973)


### Pole slipping:
![case 3](https://github.com/ThanhEthan/PINNs_Power_System_Dynamics/assets/115194407/8b35c88e-48a0-4c8f-9a79-2fcf33fb08c1)



## Language programming:
We use Julia to implement the algorithm that is running in the Jupyter Notebook, and the results are prepared in Matlab.
To run the code, please install Julia version 1.9.2, and later, Julia will instruct you how to add the necessary packet for running the code.

## Question?
Please contact Ethan Tran at email htran@aggies.ncat.edu if you have any code or implementation questions.

