# MNIST Handwritten Digit Recognition with PyTorch

This repository contains code for training a deep neural network using PyTorch to classify handwritten digits from the MNIST dataset. The MNIST dataset is a widely used benchmark dataset for image classification tasks.

## Project Overview

The main components of the project include:

- Data preprocessing: The MNIST dataset is preprocessed using torchvision `transforms` to normalize the images and convert them into tensors.
- Model architecture: A deep neural network is implemented using PyTorch's `nn.Module` class. The architecture consists of multiple layers, including convolutional layers, pooling layers, and fully connected layers.
- Training: The model is trained using the selected loss function and optimizer. Training includes iterating over the training data in batches, calculating the loss, backpropagating the gradients, and updating the model's parameters.
- Evaluation: The trained model is evaluated on the test set to measure its performance. The accuracy metric is used to assess how well the model predicts the correct digit labels.
- Model saving: The trained model is saved to disk using the `torch.save()` function, allowing it to be reused later without the need for retraining.

## Dependencies

To run the code in this repository, you need the following dependencies:

- Python 3.x
- PyTorch
- torchvision
- matplotlib

