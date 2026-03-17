# Breast Cancer Classification using PyTorch

A deep learning project that classifies breast cancer tumors as malignant or benign using Artificial Neural Networks.

## Project Summary

This is my hands-on PyTorch learning project where I built a complete neural network from scratch. I used the Breast Cancer Wisconsin dataset and achieved 100% test accuracy with a simple ANN architecture.

## What I Learned

- PyTorch tensors and autograd for automatic gradient calculation
- Creating custom Dataset classes and DataLoader for batch processing
- Building neural network models using torch.nn.Module
- Complete training pipeline with forward pass, loss calculation, backpropagation, and optimization
- Model evaluation and performance comparison

## Model Architecture

- Input Layer: 30 features
- Hidden Layer 1: 16 neurons with ReLU activation
- Hidden Layer 2: 8 neurons with ReLU activation
- Output Layer: 1 neuron with Sigmoid activation
- Loss Function: Binary Cross Entropy
- Optimizer: Adam with learning rate 0.001

## Dataset

- Breast Cancer Wisconsin Dataset
- 569 samples with 30 features each
- Binary classification (Malignant = 1, Benign = 0)
- Train-Test Split: 80-20

## Results

- Test Accuracy: 100%
- Test Loss: 0.0005

## Experiments

I tested three modifications to compare performance:

1. Increased hidden neurons from 16-8 to 64-32
2. Added one more hidden layer
3. Changed activation function from ReLU to Tanh

Finding: The original simple architecture was already optimal. Adding complexity did not improve results, showing that simpler models work better for this dataset.

## Technologies

- Python
- PyTorch
- NumPy
- Pandas
- Scikit-learn

## Key Takeaways

- Data normalization is essential for neural network training
- Simple architectures can achieve excellent results
- The standard PyTorch workflow makes training systematic and predictable

This project demonstrates fundamental PyTorch concepts through practical implementation.
