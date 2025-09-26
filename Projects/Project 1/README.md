# Project 1: Deep Learning Applications

## Overview
This repository contains the completed work for Project 1 of the Artificial Intelligence course. The project focuses on implementing advanced deep learning techniques, including image classification with pre-trained models, generative adversarial networks (GANs), and transfer learning.

## Completed Tasks

### Part I: Skin Disease Classification with VGG16 and ResNet50
- **Objective:** Classify skin diseases (Nevus, Melanoma, and Carcinoma) using VGG16 and ResNet50 architectures with and without data augmentation. 
- **Work Done:**
  - Implemented VGG16 and ResNet50 models in TensorFlow.
  - Compared classification reports for all four cases: VGG16 and ResNet50 with and without data augmentation.
  - Explained the architectures of VGG16 and ResNet50, detailing their unique design and functionality.
  - Discussed the advantages and disadvantages of data augmentation in Convolutional Neural Networks (CNNs).

### Part II: Deep Convolutional GANs (DCGAN) for CIFAR-10
- **Objective:** Create a Deep Convolutional Generative Adversarial Network (DCGAN) for the CIFAR-10 dataset.
- **Work Done:**
  - Designed and implemented a DCGAN using TensorFlow.
  - Explained the generator and discriminator architectures in detail.
  - Addressed the optimization challenge in GANs by comparing Gradient Descent and Gradient Ascent for the generator's objective function, with a practical example demonstrating the superiority of Gradient Ascent.

### Part III: Transfer Learning
- **Objective:** Explore the application of transfer learning in scenarios with small datasets.
- **Work Done:**
  - Provided a Python and TensorFlow example for employing transfer learning when:
    1. The dataset is small and **very different** from the original dataset.
    2. The dataset is small and **similar** to the original dataset.
  - Explained the appropriate strategies for fine-tuning pre-trained models in both scenarios.
