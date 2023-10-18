# MLP Projects

This repository contains implementations of neural network models for two different datasets: the MNIST dataset and the Iris dataset. Each model is developed in Python and utilizes the scikit-learn library for some data-related operations.

## Prerequisites

Make sure you have the following libraries installed:

```bash
pip install -r requirements.txt
```

## Directory Structure

- **mnist_mlp:**
  This directory contains the implementation of a Multilayer Perceptron (MLP) for MNIST dataset classification. The model is trained to recognize handwritten digits.

- **iris_mlp_relu:**
  In this directory, you will find an implementation of an MLP for Iris dataset classification, using the ReLU activation function.

- **iris_mlp_tanh:**
  It contains a similar implementation to the previous one, but it uses the Hyperbolic Tangent (tanh) activation function instead of ReLU.

- **iris_mlp_sigmoid:**
  Here is an implementation of the MLP for the Iris dataset, this time using the Sigmoid activation function.

## File Descriptions

- **`mnist_mlp.ipynb`:**
  This file contains the implementation of the neural network for the MNIST dataset. The model is trained using the ReLU activation function and is capable of recognizing handwritten digits.

- **`iris_mlp_relu.ipynb`:**
  Implementation of the MLP for the Iris dataset with ReLU activation.

- **`iris_mlp_tanh.ipynb`:**
  Implementation of the MLP for the Iris dataset with the Hyperbolic Tangent (tanh) activation function.

- **`iris_mlp_sigmoid.ipynb`:**
  Implementation of the MLP for the Iris dataset with the Sigmoid activation function.

## How to Use

Each directory contains a Jupyter file corresponding to the model. To run a specific model, simply navigate to the desired directory and execute the corresponding cell.

Make sure to have Python and the required libraries installed before running the scripts.
