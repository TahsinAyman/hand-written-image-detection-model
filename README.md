# Hand Digit Recognition

A hand-written digit recognition project built from the ground up using raw mathematics and calculus, without relying on a high-level deep learning framework for the core logic. This project explores how neural networks learn to classify digits from 0 to 9 through linear algebra, optimization, and gradient-based training.

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue" alt="Python 3.10+" />
  <img src="https://img.shields.io/badge/ML-From%20Scratch-orange" alt="Machine Learning from scratch" />
  <img src="https://img.shields.io/badge/Math-Calculus%20%26%20Linear%20Algebra-green" alt="Math and calculus" />
</p>

## Overview

This project focuses on building a digit classifier using a simple neural network trained on the MNIST-like dataset. The goal is not just to achieve accuracy, but to understand the mathematics behind learning:

- Forward propagation
- Loss functions
- Backpropagation
- Gradient descent
- Weight updates
- Activation functions

The implementation is intentionally educational and transparent, showing how each step connects to calculus and linear algebra.

## Why This Project?

Many modern ML projects hide the underlying mechanics behind framework abstractions. This project is designed to make those mechanics visible and understandable.

It demonstrates:

- How images are flattened into vectors
- How weights transform input into predictions
- How a scalar loss is minimized with gradients
- How neural networks update themselves through calculus

## Core Mathematics

The model learns by minimizing a loss function such as cross-entropy:

L = - (1/n) Σ y_i log(ŷ_i)

The network updates its parameters using gradient descent:

W := W - η ∂L/∂W

and the gradients are computed through backpropagation using the chain rule:

∂L/∂W = ∂L/∂a · ∂a/∂z · ∂z/∂W

This project transforms abstract concepts into practical code, making it easier to see how machine learning is really working.

## Features

- Digit classification for 0–9
- Neural network implemented from scratch
- Manual matrix operations and vectorized computations
- Training loop with gradient descent
- Visualization of training progress
- Lightweight, readable, educational code structure
- No black-box deep learning library for the learning core
