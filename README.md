# Feedforward vs Spiking Neural Networks — From Scratch

This repository contains a from-scratch implementation of a Feedforward Neural Network (FFNN) and a Spiking Neural Network (SNN), built using NumPy and basic scientific Python tools.

The project focuses on understanding *how* neural networks make decisions, rather than optimizing performance using high-level frameworks.

---

## Motivation

Most neural network workflows rely on abstraction-heavy libraries that hide internal dynamics.
This project aims to:

- Build neural networks step by step from first principles
- Visualize learning behavior and decision boundaries
- Compare probabilistic (ANN) and temporal (SNN) decision mechanisms
- Develop intuition about model behavior and confidence

Accuracy is secondary to interpretability.

---

## Implemented Models

### 1. Feedforward Neural Network (FFNN)
- Fully connected layers
- ReLU activations
- Softmax output
- Trained using gradient descent
- Implemented using NumPy only

Includes:
- Training loss and accuracy curves
- Decision boundary visualization
- Interactive digit-drawing canvas for live inference

---

### 2. Spiking Neural Network (SNN)
- Rate-coded input spikes
- Leaky Integrate-and-Fire (LIF) neurons
- Spike accumulation over time
- Decision based on spike counts

Includes:
- Spike raster visualization
- Output neuron spike histograms
- Comparison with ANN predictions

---

## ANN vs SNN Comparison

For the same handwritten digit input:
- The ANN produces a probability distribution over classes
- The SNN produces spike counts over time

This highlights the difference between:
- **Instantaneous probabilistic inference**
- **Temporal evidence accumulation**

---



