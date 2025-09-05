# GEN_AI

# Generative Adversarial Networks (GANs)

This repository contains implementations of various **Generative Adversarial Networks (GANs)** using **TensorFlow/Keras** and **PyTorch** on the **MNIST dataset**.  
Each folder contains code and Jupyter notebooks for training and experimenting with different GAN architectures.  

---

## Folder Structure

- **Vanilla GAN**  
  Basic GAN implementation with a simple Generator and Discriminator.

- **DC GAN**  
  Deep Convolutional GAN with convolutional layers for improved image generation.

- **C GAN**  
  Conditional GAN where generation is conditioned on class labels (digits in MNIST).

- **CYCLE GAN**  
  CycleGAN implementation for unpaired image-to-image translation.  
  Example: MNIST digits split into two domains (0–4 ↔ 5–9).

- **STYLE GAN**  
  StyleGAN-inspired model with mapping network and style modulation.  
  Generates MNIST digits starting from a learned constant.

---

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/FenilVadher/GEN_AI.git
cd GEN_AI
