# Conditional-GAN-on-MNIST
Implementation of a Conditional Generative Adversarial Network (cGAN) on the MNIST dataset using PyTorch. The generator produces handwritten digits conditioned on class labels (0–9).
This project implements a Conditional Generative Adversarial Network (cGAN) using PyTorch to generate MNIST digit images conditioned on class labels (0–9).

## Features
- Conditional Generator and Discriminator networks using label embeddings
- Training on the MNIST dataset
- Visualizing generated images for each digit (0-9)
- Fully compatible with Google Colab and GPU usage

## Installation
```bash
pip install torch torchvision matplotlib
