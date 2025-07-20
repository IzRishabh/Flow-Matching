# Flow-Matching
PyTorch implementation of Flow Matching for generative modeling on a 2D checkerboard dataset.

Goal: Implement and demonstrate Flow Matching for generative modeling.
Data: Generates a synthetic 2D checkerboard dataset as the target distribution.
Model: Utilizes a Multi-Layer Perceptron (MLP) to learn the vector field of the continuous flow.
Training: Trains the MLP to predict the vector field that maps points from a simple distribution (noise) to the target data distribution over time.
Sampling: Samples new data points by simulating the learned flow starting from noise, effectively generating data that resembles the target checkerboard pattern.
Framework: Implemented using PyTorch.
