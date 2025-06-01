# CAT-VAE: A Cross-Attention Transformer-Enhanced Variational Autoencoder for Improved Image Synthesis

This repository contains the implementation and results of the paper titled **"CAT-VAE: A Cross-Attention Transformer-Enhanced Variational Autoencoder for Improved Image Synthesis"**.

## Overview

CAT-VAE is a novel generative model that integrates a cross-attention transformer mechanism into the traditional Variational Autoencoder (VAE) framework to enhance image synthesis quality, particularly in medical imaging domains. The model improves reconstruction fidelity and generative realism, as demonstrated on datasets such as ultrasound breast cancer images and BRATS 2020 MRI data.

## Repository Contents

- `VAE.ipynb`: Jupyter notebook containing the implementation of the baseline vanilla VAE model, used as a comparison benchmark.
- `CAT-VAE.ipynb`: Jupyter notebook implementing the proposed CAT-VAE model with cross-attention transformer enhancements.
- Results and evaluation metrics (SSIM, PSNR, FID, MSE), as well as classification using CANN, are included within the notebooks and discussed in the accompanying paper.

## Getting Started

To run the notebooks, please ensure you have the following dependencies installed:

- Python 3.7+
- PyTorch
- NumPy
- Matplotlib
- scikit-image
- (Other dependencies as per the notebooks)

