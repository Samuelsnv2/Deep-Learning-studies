# Iris Flower Classification with Perceptron Models

## Introduction

This project focuses on implementing Perceptron models for the classification of Iris flowers based on the Iris dataset. The directory contains three different implementations of Perceptron models, each utilizing a different activation function: sigmoid, hyperbolic tangent (tanh), and binary.

## Project Overview

- **Objective**: Classify Iris flowers into different species (setosa, versicolor, virginica) based on sepal and petal measurements.
- **Perceptron Model**: The Perceptron is a simple neural network model used for binary classification tasks.
- **Activation Functions**: Three versions of the Perceptron were implemented, each with a different activation function: sigmoid, hyperbolic tangent (tanh), and binary.

## Project Structure

The project structure consists of the following components:

- **iris_perceptron_sigmoid.py**: Implementation of the Perceptron model with the sigmoid activation function.
- **iris_perceptron_tanh.py**: Implementation of the Perceptron model with the hyperbolic tangent (tanh) activation function.
- **iris_perceptron_binary.py**: Implementation of the Perceptron model with the binary activation function.
- **iris.csv**: The Iris dataset in CSV format.
- **requirements.txt**: List of required Python libraries.

## Instructions

To run and analyze the Perceptron models:

1. Clone this repository to your local computer:

   ```bash
   git clone https://github.com/yourusername/iris-flower-classification
   ```

2. Navigate to the project directory:

    ```
    bash
    cd iris-flower-classification
    ```
    
    Install the necessary Python libraries:
    ```
    bash
    pip install -r requirements.txt
    ```

3. Execute each of the following scripts to train and test the Perceptron models:

- iris_perceptron_sigmoid.py: Sigmoid activation function.
- iris_perceptron_tanh.py: Tanh activation function.
- iris_perceptron_binary.py: Binary activation function.

## Model Analysis

### Perceptron with Sigmoid Activation Function
The Perceptron model with the sigmoid activation function showed relatively low performance in classifying Iris flowers. The accuracy achieved suggests that the sigmoid function may not be the best choice for this specific problem.

### Perceptron with Tanh Activation Function
The Perceptron with the tanh activation function also did not achieve satisfactory performance in classifying Iris flowers. The accuracy achieved indicates that the tanh function may not be suitable for this classification task.

### Perceptron with Binary Activation Function
The Perceptron with the binary activation function performed the best among the implementations. It achieved significantly higher accuracy in classifying Iris flowers. However, it is important to note that there is still room for improvement.

## Suggestions for Improvements
Based on the results, we suggest exploring more advanced machine learning approaches, such as deep neural networks (Deep Learning) or more complex classification algorithms, to achieve better performance in classifying Iris flowers. Additionally, tuning hyperparameters such as learning rate and the number of iterations may help improve the performance of the Perceptron models.

## Acknowledgments
This project was inspired by the well-known Iris dataset and Perceptron concepts. We thank the scikit-learn library for providing the Iris dataset.

## About the Iris Dataset
The Iris dataset is a widely-used dataset in the field of machine learning. It contains 150 samples of Iris flowers, with four features: sepal length, sepal width, petal length, and petal width. The dataset includes three species: setosa, versicolor, and virginica.

## Credits

This project was developed as part of a machine learning learning journey and serves as a practical example of using a Perceptron with the tanh activation function for classification tasks.

Feel free to explore the code and modify it for your own projects. If you have any questions or suggestions, please don't hesitate to reach out.

Happy coding!
