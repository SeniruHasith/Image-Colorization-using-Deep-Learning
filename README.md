# Image Colorization using Deep Learning (GANs)

This project implements a deep learning model for converting grayscale images to colored images using Generative Adversarial Networks (GANs). The model learns colorization patterns from annotated datasets, producing high-quality colorized images by using the adversarial training approach.

## Overview

The model uses a Generative Adversarial Network (GAN) to perform image colorization. The GAN consists of two networks: a **generator** that generates colored images from grayscale inputs, and a **discriminator** that evaluates how realistic the generated images are compared to real color images. The generator improves through adversarial training, eventually learning to produce realistic colorized images from grayscale ones.

## Features

- **Grayscale to Colored Image Conversion**: Converts black-and-white images into realistic colored images using GANs.
- **Generative Adversarial Network (GAN)**: The generator learns to produce colorized images, and the discriminator evaluates their realism to improve the generator's performance.
- **Custom Neural Network Architecture**: Utilizes a specialized GAN architecture tailored for image colorization.

## Setup

Follow these steps to set up the project on your local machine:

### 1. Clone the Repository

```bash
git clone https://github.com/yourusername/image-colorization-gan.git
cd image-colorization-gan
