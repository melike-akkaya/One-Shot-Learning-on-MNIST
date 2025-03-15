# One-Shot Learning with MNIST

## Overview
This project implements a one-shot learning model for binary classification using the MNIST dataset. The main objective is to train a meta-model that can synthesize class-specific classifier parameters from just a single training example per class. This approach is tested using digits 0-5 for training and 6-9 for testing to evaluate the model's performance on unseen classes.

## Implementation Details
- **Framework Used:** PyTorch
- **Training:** The model is trained by sampling one example per class and using a set of query examples to update the meta-model iteratively.
- **Testing:** The effectiveness of the learned model is tested by sampling test examples and measuring classification accuracy.

## Requirements
- Python 3.x
- PyTorch
- Matplotlib (for visualization)
