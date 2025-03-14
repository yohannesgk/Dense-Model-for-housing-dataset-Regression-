# Dense-Model-for-housing-dataset-Regression-

# California Housing Regression

This repository contains a deep learning regression model for predicting house values from the [California Housing dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset). The final model achieves:

- **Mean Absolute Error (MAE):** 0.329985
- **Mean Squared Error (MSE):** 0.240546
- **R-squared (R²):** 0.747050

## Table of Contents

- [Overview](#overview)
- [Data](#data)
- [Results](#results)
- [How to Run](#how-to-run)
- [License](#license)

---

## Overview

This project demonstrates how to train a regression model using Keras on California Housing dataset.

1. Loads and preprocesses the data (normalization, train-test split).
2. Builds a neural network (or another regressor).
3. Trains the model and evaluates performance using MAE, MSE, and R² metrics.
4. Visualizes training history and predictions.

---

## Data

The California Housing dataset contains information about house prices and various features like:
- Median Income
- House Age
- Number of Rooms
- Latitude/Longitude
- etc.

**Source**: [scikit-learn’s California Housing dataset](https://scikit-learn.org/stable/datasets/real_world.html#california-housing-dataset)


### Training Curves

Below are example training curves showing how the training and validation loss, as well as MAE, change over epochs:

![Training Metrics](images/metrics.png)

---

## Results

After training, we evaluated on the test set:

- **MAE**: 0.329985  
- **MSE**: 0.240546  
- **R²**: 0.747050  

A higher R² (close to 1.0) indicates a good fit, while the relatively low MAE suggests the model is reasonably accurate in predicting housing values.

### Predictions vs. Actual

Below is a plot comparing actual vs. predicted values and training values for a the test data:

![ca_graph](https://github.com/user-attachments/assets/c03b9e40-7d47-4d0c-850f-40a640c3ca39)
![ca_match](https://github.com/user-attachments/assets/18f0d98f-638c-42cd-87f1-e160361d64fb)



