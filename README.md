# Multilayer Perceptron (MLP) Project

## Overview
This repository contains an implementation of a Multilayer Perceptron (MLP) designed to classify images from the CIFAR-10 dataset. The project demonstrates key steps such as data preparation, model building, training, evaluation, and visualization of predictions.

## Features
- **Data Preparation:**
  - Normalization of image data.
  - Conversion of labels to categorical format.
- **Model Architecture:**
  - Input layer: Handles CIFAR-10 image dimensions (32x32x3).
  - Two dense hidden layers with ReLU activation.
  - Output layer with softmax activation for multi-class classification.
- **Training:**
  - Configurable training loop using Adam optimizer and categorical cross-entropy loss.
  - Real-time accuracy tracking during training.
- **Evaluation:**
  - Performance metrics such as accuracy.
  - Visualization of predictions versus actual labels.

## Prerequisites
- Python 3.x
- Libraries:
  - TensorFlow/Keras
  - NumPy
  - Matplotlib

## Installation
1. Clone the repository:
   ```bash
   https://github.com/Oladipo06/mlp.git
   cd mlp
