# Variational Autoencoder (VAE) with MNIST

This project demonstrates how to implement a Variational Autoencoder (VAE) using PyTorch and train it on the MNIST dataset. A VAE is a powerful generative model that learns to encode and decode data, enabling the generation of new, similar data samples.

## Project Description

The aim of this project is to explore how the size of the latent representation in a VAE affects its ability to generate realistic images. The VAE works by first passing the data through an encoder function, which compresses the data into a latent representation. This representation is then passed through a decoder, which reconstructs the original data from the compressed form. By sampling from the latent space, the VAE can generate new images.

## Objectives

1. **Train a VAE on MNIST data:** Utilize the PyTorch framework to train a VAE on the MNIST dataset, which consists of handwritten digit images.
2. **Explore latent representation sizes:** Experiment with at least three different sizes of the latent representation to observe how it impacts the quality of generated images.
3. **Evaluate reconstruction quality:** Assess the VAE's performance in reconstructing the input images for each latent representation size, aiming to determine the smallest latent space that still maintains high-quality image generation.

## Steps

1. **Data Preparation:** Load and preprocess the MNIST dataset. A smaller subset of the MNIST dataset is used for quicker iterations and reduced runtime.
2. **Model Architecture:** Define the encoder and decoder networks for the VAE. The chosen architecture uses convolutional layers, making it suitable for image data as it captures spatial features effectively.
3. **Training:** Train the VAE using the MNIST training data.
4. **Latent Space Exploration:** Experiment with different sizes of the latent representation.
5. **Evaluation:** Evaluate the reconstruction quality for each latent representation size and analyze the results.

## Results

The results of this project will include:

- Training logs and loss curves for the different latent representation sizes.
- Generated images and their corresponding latent space sizes.
- A comparative analysis of the reconstruction quality for each latent representation size.

This project aims to provide insights into how the size of the latent representation in a VAE influences the quality of generated images, helping to determine the optimal balance between compression and image quality.
