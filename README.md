
# Variational Autoencoders (VAEs) on MNIST Dataset

This repository contains implementations and experiments with various types of Variational Autoencoders (VAEs) applied to the MNIST dataset. VAEs are generative models that learn to encode and decode data in a probabilistic manner, making them particularly useful for image generation tasks.

## Table of Contents

- [Introduction](#introduction)
- [Implemented Models](#implemented-models)
- [Dependencies](#dependencies)


## Introduction

Variational Autoencoders are a class of generative models that learn to represent data in a latent space. This repository explores different types of VAEs, including Convolutional VAEs, Dense VAEs, and Conditional VAEs, applied to the MNIST dataset. Each model is implemented and tested for its ability to generate realistic digit images.

## Implemented Models

1. **Vanilla VAE**: A basic VAE architecture using fully connected layers.
2. **Convolutional VAE**: Utilizing convolutional layers for image-related tasks.
3. **Conditional VAE**: A VAE that conditions the generation on a specific digit class.

## Dependencies

Ensure you have the following dependencies installed:

- Python 3.x
- TensorFlow
- NumPy
- Matplotlib
- Jupyter (for running notebooks)

## The latent space clusters of different digit classes:

<img src="./Result/the%20latent%20space%20clusters%20different%20digit%20classes_vanilla.png" width="200"/> 
**Vanilla VAE**

<img src="./Result/the%20latent%20space%20clusters%20different%20digit%20classes_Conv.png" width="200"/> 
**Convolutional VAE**

<img src="./Result/the%20latent%20space%20clusters%20different%20digit%20classes_conditional.png" width="200"/> 
**Conditional VAE**

## Grid of sampled digit images generated by different latent variables:

<img src="./Result/Grid%20of%20sampled%20digit%20images%20generated%20by%20different%20latent%20variables_vanilla.png" width="200"/> 
**Vanilla VAE**

<img src="./Result/Generated%20Samples%20by%20different%20latent%20variables%20of_Convolutional%20VAE.png" width="200"/> 
**Convolutional VAE**

<img src="./Result/the%20generated%20samples%20of%20CVAE.png" width="200"/> 
**Conditional VAE**

## The generated sample with VAEs:

<img src="./Result/The%20output%20of%20(0,0)_vanilla.png" width="200"/> 
**Vanilla VAE**

<img src="./Result/The%20output%20of%20(0,0)%20for%20Convolutional%20VAE.png" width="200"/> 
**Convolutional VAE**

<img src="./Result/CVAE.png" width="200"/> 
**Conditional VAE**


