# American Option Pricing with Longstaff-Schwartz & Broadie-Anderson

This repository implements pricing algorithms for **American options** using:
- **Longstaff-Schwartz algorithm (LS)** with **regression-based approximation**.
- **Broadie-Andersen method** for resimulating paths after stopping.
- **Neural Networks (FNNs)** as an alternative to the regression approach.

## Features

- **Methods**: 
  - **LS (Least Squares)**: Uses linear regression for continuation value approximation.
  - **FNN (Feedforward Neural Networks)**: Replaces regression with a neural network.
  - **Broadie-Andersen**: Resimulates paths after the optimal stopping point for more accurate pricing.
- **Visualizations**: Plots **optimal exercise trajectories**, and compares **continuation values** vs **payoffs**.

### **Important Note**

The algorithms implemented in this repository assume that **dividends are continuously reinvested**. As a result, these methods are **not suitable for pricing American call options** with a **dividend yield** where the dividends are paid out (not reinvested), as they affect the exercise strategy and underlying asset price evolution differently. For such cases, alternative models incorporating dividend payouts need to be used.
