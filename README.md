Deep Learning Cat Classifier

This project implements a deep learning model for image classification using a neural network built from scratch using Python and libraries like NumPy and OpenCV.

Project Overview

This repository contains Python scripts for two neural network models:

Two-layer Neural Network:

A simple neural network with two layers (one hidden layer).

Implements forward propagation, backward propagation, and parameter updates.

Achieves high accuracy on a cat vs non-cat image dataset.


L-layer Neural Network:

A deeper neural network with multiple hidden layers.

Uses deep learning techniques for improved accuracy and performance.

Includes functions for forward propagation, backward propagation, and gradient descent optimization.

Requirements

Python 3.x
NumPy
matplotlib
scipy
h5py
PIL (Python Imaging Library)
Jupyter Notebook (optional for viewing and running the notebooks)

Installation

Clone the repository:

bash
git clone https://github.com/namanthecoder01/Cat_Classifier.git

cd deep-learning-image-classifier

Install dependencies:
pip install -r requirements.txt

Usage

Two-layer Neural Network:

Run two_layer_model.ipynb to train and test the two-layer neural network.
Adjust parameters and iterations to see different training results.
Evaluate model accuracy using test datasets.

L-layer Neural Network:

Run l_layer_model.ipynb to train and test the deeper L-layer neural network.
Modify layers and iterations for experimenting with different network architectures.
Test the model with your own images using the provided example.

Results

Two-layer Model:

Achieved an accuracy of nearly 72% on the test dataset after 2500 iterations.

L-layer Model:

Achieved an accuracy of 80% on the test dataset after 2500 iterations.

Successfully classified a custom image with 100% accuracy (e.g., predicted a "cat" image correctly).

Future Enhancements

Implement batch normalization and dropout techniques for improving model robustness.

Expand dataset and experiment with different image sizes and types.

Deploy the models using frameworks like TensorFlow or PyTorch for scalable applications.

Author

Naman Jain
