![Python](https://img.shields.io/badge/language-python-blue.svg)
![PyTorch](https://img.shields.io/badge/framework-PyTorch-orange.svg)
# Visual Concept Learning with DBN, CNN, and FNN

## Overview

In this project, we explore computational models of visual concept learning with a focus on comparing Deep Belief Networks (DBN), Convolutional Neural Networks (CNN), and Feedforward Neural Networks (FNN). The main objective is to investigate the ability of different models to learn and represent visual concepts using the **FashionMNIST** dataset. Additionally, we analyze the models' performance, robustness to noisy data, and internal representations.

We evaluate the performance of the models on:
- **DBN** (with and without fine-tuning)
- **CNN**
- **FNN**

The project is based on Python code developed during lab practices.

## Methodology

### Deep Belief Networks (DBN)
- DBNs are neural networks that learn hierarchical representations of data through multiple layers of hidden units.
- They can be used for both supervised and unsupervised learning tasks.
- In this project, we apply DBNs to the **FashionMNIST** dataset with and without fine-tuning, comparing their performance to CNN and FNN models.

### Convolutional Neural Networks (CNN)
- CNNs are designed for image classification tasks and perform feature extraction through a series of convolutional layers.
- The layers extract local features (e.g., edges) and progressively learn abstract features for classification.
- CNNs are widely used in image processing and perform well on image classification tasks.

### Feedforward Neural Networks (FNN)
- FNNs are a type of neural network where data moves in one direction from input to output.
- They serve as a simpler baseline model for comparison with more complex architectures like DBNs and CNNs.

### Experiment Design
The project uses the **FashionMNIST** dataset, which contains 28x28 grayscale images of clothing items. The models are evaluated based on:
1. **Accuracy**: Classification performance on both clean and noisy images.
2. **Noise Resilience**: How well the models handle noisy input data.
3. **Model Complexity**: Comparison of training time and computational efficiency.

## Goals

1. **Model Comparison**: Compare DBNs, CNNs, and FNNs based on supervised (CNN, FNN) and unsupervised (DBN) learning methods.
2. **Noise Resilience**: Evaluate how well the models perform under noisy conditions, especially in terms of accuracy on noisy data compared to clean data.
3. **Complexity and Resilience Balance**: Identify which model offers the best trade-off between complexity, noise resilience, and accuracy.

## Results and Analysis

- **Accuracy**: Results show how each model performs on clean versus noisy data.
- **Resilience to Noise**: Analysis of how noise in the dataset impacts the models' ability to classify images.
- **Complexity**: A comparison of the computational cost of each model, including training time and resources.

## Installation

To set up the project locally, clone the repository and install the necessary dependencies:

```bash
git clone https://github.com/shararezr/DeepBeliefNetwork.git
cd DeepBeliefNetwork
pip install -r requirements.txt
