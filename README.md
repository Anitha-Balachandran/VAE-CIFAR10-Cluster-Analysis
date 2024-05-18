# Mini-Project Summary: Variational Autoencoder on CIFAR10 Dataset

## Objective:
The objective of this mini-project is to apply a Variational Autoencoder (VAE) on the CIFAR10 dataset. The project aims to use a VAE architecture with a minimum of 4 convolutional layers in the encoder and 4 deconvolutional layers (Conv2DTranspose/upscale) in the decoder. Additionally, the project will analyze how the latent space clusters different classes of the training data.

## Details:

### VAE Architecture
- **Encoder:** Implement a VAE encoder with a minimum of 4 convolutional layers to encode the input data into a latent space representation.
- **Decoder:** Develop a VAE decoder with 4 deconvolutional layers (Conv2DTranspose/upscale) to reconstruct the input data from the latent space.
- **Number of Epochs:** Train the VAE model for a minimum of 100 epochs to ensure convergence and effective learning of latent space representations.

### Analysis of Latent Space
- **Cluster Analysis:** Analyze how the latent space clusters different classes of the CIFAR10 training data. Visualize and interpret the clustering patterns to understand the distribution and representation of data in the latent space.

## Conclusion:
This mini-project focuses on applying a Variational Autoencoder architecture on the CIFAR10 dataset, emphasizing the use of convolutional and deconvolutional layers in the encoder and decoder, respectively. The project also explores the clustering behavior of the latent space to gain insights into the learned representations of the input data.
