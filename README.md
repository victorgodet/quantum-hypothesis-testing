# quantum-hypothesis-testing

This repository contains a Mathematica notebook used for the paper "Quantum hypothesis testing in many-body systems" by Jan de Boer, Victor Godet, Jani Kastikainen and Esko Keski-Vakkuri (https://arxiv.org/abs/2007.11711).

This notebook implements measurements of a qubit in the context of (asymmetric) quantum hypothesis testing. The measurement is applied to n copies of the system and optimized to distinguish between two states of the qubit.

It contains an implementation of the optimal measurement and of a suboptimal but simpler measurement: the likelihood ratio test (which can also be performed with the quantum circuit given in Figure 5). These two measurements are compared and plots (given in Figure 6) are generated. 

It also computes the various information quantities (the relative entropy and the relative entropy variance) appearing in these measurements.
