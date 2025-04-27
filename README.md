# CNN_with_PyTorch-MNIST-project
# MNIST Digit Classification using CNN with PyTorch

[![PyTorch](https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white)](https://pytorch.org/)
[![Python](https://img.shields.io/badge/Python-3.6%2B-blue.svg)](https://www.python.org/)

A Convolutional Neural Network implementation for classifying handwritten digits from the MNIST dataset using PyTorch, achieving **98%+ accuracy**.

![Sample Prediction](https://via.placeholder.com/150x150/808080/ffffff?text=9) *Example prediction from test set*

## Overview
This project demonstrates image classification using a custom CNN architecture built with PyTorch. The model is trained on the MNIST dataset containing 60,000 training and 10,000 testing 28x28 grayscale images of handwritten digits (0-9).

## Key Features
- **MNIST Dataset**: Standard benchmark dataset for digit recognition
- **CNN Architecture**: Custom network with:
  - Two convolutional layers
  - Dropout regularization
  - Max-pooling layers
  - Fully connected layers
- **Training Pipeline**: Includes data loading, augmentation, and GPU acceleration
- **Evaluation Metrics**: Accuracy tracking and loss visualization
- **Interactive Prediction**: Sample test image prediction visualization

## Requirements
- Python 3.6+
- PyTorch 1.0+
- torchvision
- NumPy
- Matplotlib
- Jupyter Notebook

## Installation
```jupyter notebook CNN_with_Pytorch(MNIST).ipynb
# Clone repository
git clone https://github.com/Yusif617/CNN_with_PyTorch-MNIST.git

# Install dependencies
pip install torch torchvision numpy matplotlib jupyter
