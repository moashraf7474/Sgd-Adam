# SGD vs Adam Optimizer Comparison

## Description

This project demonstrates the difference between two popular optimizers in deep learning:

- **SGD (Stochastic Gradient Descent)**  
- **Adam (Adaptive Moment Estimation)**

Using the **MNIST dataset** (handwritten digits), we train a simple Multi-Layer Perceptron (MLP) model twice:

1. Using **SGD**
2. Using **Adam**

We compare their performance in terms of:

- Loss curve during training
- Accuracy on test data
- Convergence speed
- Stability of learning

This project is designed to **visually and practically show the difference** between the two optimizers, making it easy to understand their behavior.

---

## Dataset

- **MNIST** dataset of handwritten digits (0-9)  
- Number of samples:
  - Training: 60,000
  - Testing: 10,000
- Image size: 28 × 28 pixels  
- Source: [PyTorch torchvision datasets](https://pytorch.org/vision/stable/datasets.html)

---

## Requirements

- Python 3.8+
- PyTorch
- Torchvision
- Matplotlib

Install the required libraries:

```bash
pip install torch torchvision matplotlib
