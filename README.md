# American Option Pricing with Longstaff-Schwartz & Broadie-Anderson

This repository implements pricing algorithms for **American options** using:
- **Longstaff-Schwartz algorithm (LS)** with **regression-based approximation**.
- **Broadie-Andersen method** for resimulating paths after stopping.
- **Neural Networks (FNN)** as an alternative to the regression approach.

## Features

- **Option Types**: Supports both **call** and **put** options.
- **Methods**: 
  - **LS (Least Squares)**: Uses linear regression for continuation value approximation.
  - **FNN (Feedforward Neural Networks)**: Replaces regression with a neural network.
  - **Broadie-Andersen**: Resimulates paths after the optimal stopping point for more accurate pricing.
- **Visualizations**: Plots **optimal exercise trajectories**, and compares **continuation values** vs **payoffs**.
