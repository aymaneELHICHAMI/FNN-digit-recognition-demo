# MNIST Digit Classifier with PyTorch
This Jupyter notebook implements a simple fully connected neural network using PyTorch to classify handwritten digits from the MNIST dataset.

## Overview
- Dataset: MNIST (28x28 grayscale digit images)
- Model: Feedforward neural network with one hidden layer
- Framework: PyTorch
- Device: Uses GPU if available

## Key Components
- Data Loading: Uses torchvision.datasets.MNIST with DataLoader for batching.
- Model Architecture:
    - Input layer: 784 neurons (28x28)
    - Hidden layer: 100 neurons with ReLU activation
    - Output layer: 10 classes (digits 0–9)
- Training:
    - Loss: CrossEntropyLoss (includes softmax)
    - Optimizer: Adam
    - Epochs: 6
- Evaluation: Accuracy computed on the test set

## How to Run
- Install PyTorch and torchvision
- Run the notebook to train and evaluate the model
- Optionally visualize sample digits and test predictions

## Example Result
- Expected accuracy: ~97% on test set after 6 epochs