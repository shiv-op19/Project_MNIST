# Handwritten Digit Classification using Artificial Neural Networks

## Project Overview

This project implements a Deep Learning model to classify handwritten digits from the MNIST dataset. The model is built using TensorFlow and Keras and is capable of recognizing digits from 0 to 9.

## Problem Statement

Handwritten digit recognition is a fundamental computer vision task. The objective of this project is to train a neural network that can accurately classify grayscale images of handwritten digits into one of ten classes (0–9).

## Dataset

The MNIST dataset consists of:

* 60,000 training images
* 10,000 testing images
* 28 × 28 grayscale pixel images
* 10 output classes (digits 0–9)

## Technologies Used

* Python
* NumPy
* Matplotlib
* TensorFlow
* Keras

## Deep Learning Workflow

1. Load the MNIST dataset
2. Normalize pixel values
3. Build an Artificial Neural Network (ANN)
4. Train the model on the training data
5. Evaluate model performance on test data
6. Predict handwritten digits

## Model Architecture

* Input Layer (28 × 28 images)
* Flatten Layer
* Dense Hidden Layer(s) with ReLU Activation
* Output Layer with Softmax Activation

## Loss Function and Optimizer

* Loss Function: Sparse Categorical Crossentropy
* Optimizer: Adam
* Metric: Accuracy

## Results

* Test Accuracy: 97.9% 
* Successfully classifies handwritten digits from 0 to 9.

## Key Concepts Demonstrated

* Image Classification
* Neural Networks
* Multiclass Classification
* TensorFlow/Keras Model Development
* Deep Learning Fundamentals

## Author

Shivam
