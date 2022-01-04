# CovidAutoEncoder
CS 4641 Final Project
(its not that deep)

# Overview
Created and tested various autoencoder architectures (Convolutional, Variational, Linear) to learn latent representations of
SARS-Cov-2 genomes and most importantly: the latent differences between the variant genomes.

We trained the autoencoder on more prevalent strains (Alpha and Delta). Once the model was capable of learning lower dimensional latent representations without losing information, we encoded Omicron genomes into these representations and were able to clearly distinguish the variants with a simple PCA.

