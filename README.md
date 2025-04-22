# American Option Pricing with Longstaff-Schwartz & Broadie-Andersen

This repository implements pricing algorithms for **American options** using :

## Algorithms

- **Longstaff-Schwartz algorithm (LS)** for the Primal Problem (lower bound).
- **Broadie-Andersen algorithm** for the Dual Problem (upper bound).

## Methods

- **Regression-based approximation**
- **Neural Networks (FNNs)** as an alternative to the regression approach.

## Features

- **Methods**: 
  - **LS (Least Squares)**: Uses linear regression for continuation value approximation.
  - **FNN (Feedforward Neural Networks)**: Replaces regression with a neural network.
- **Visualizations**: Plots **optimal exercise trajectories**, and compares **continuation values** vs **payoffs**.

### **Important Note**

The algorithms implemented in this repository assume that **dividends are continuously reinvested**. As a result, these methods are **not suitable for pricing American call options** and **American put options** with dividends not reinvested. 
