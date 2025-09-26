# Assignment 1: Optimization, SMOTE, and DNN

## Overview
This document outlines the work completed for Assignment 1 of the Artificial Intelligence course at the University of Tehran. The assignment focused on understanding and implementing core concepts in deep learning and machine learning, including optimizers, handling imbalanced datasets, and building classification models.

## Completed Tasks

### 1. Mathematical Intuition Behind Optimizers
I thoroughly analyzed and explained the mathematical foundations of three widely used optimization algorithms for training deep neural networks:
- **Stochastic Gradient Descent + Momentum (SGD + Momentum):** Covered the mechanism of momentum addition to standard SGD, its effect on convergence, and how it overcomes oscillations in the optimization path.
- **Adagrad:** Discussed the adaptive learning rate adjustment, its benefits for sparse data, and its limitations related to aggressive learning rate decay.
- **RMSprop:** Explained how it resolves the limitations of Adagrad by introducing a decaying average of squared gradients, leading to better performance in non-convex optimization problems.

### 2. Optimizer Comparison in Real-World Applications
I explored the literature to compare the performance of SGD + Momentum, Adagrad, and RMSprop in practical scenarios. My analysis included:
- Use cases where each optimizer is most effective.
- A detailed comparison of their strengths and weaknesses, particularly in terms of convergence speed, computational efficiency, and adaptability to different data distributions.

### 3. Handling Imbalanced Datasets Using SMOTE
I tackled the challenge of imbalanced datasets by:
- Providing a mathematical explanation of the **Synthetic Minority Oversampling Technique (SMOTE)**, including its interpolation process for generating synthetic samples of minority classes.
- Implementing SMOTE using Python and TensorFlow to demonstrate its effectiveness in improving model performance. The implementation includes:
  - A detailed step-by-step application of SMOTE on an example dataset.
  - Visualizations of the dataset before and after applying SMOTE to illustrate the distribution changes.

### 4. Classification Model with Deep Neural Networks
Using the dataset provided for the assignment, I developed and evaluated a classification model with the following features:
- Designed a **Deep Neural Network (DNN)** architecture for classification, with careful tuning of hyperparameters.
- Integrated **SMOTE** to handle class imbalance in the training data.
- Trained the model with **Adagrad** and **RMSprop** optimizers separately and compared their performance in terms of:
  - Training and validation accuracy.
  - Training and validation loss.
- Plotted detailed performance metrics to visualize the model's behavior during training and validation phases.
