# Vision-Transformer-Image-Classification
A Vision Transformer (ViT) implementation for image classification using CIFAR-10 dataset, leveraging HuggingFace's Trainer API for computational efficiency
# Vision Transformer for Image Classification

## Overview
This repository contains an implementation of the Vision Transformer (ViT) model, a novel architecture leveraging self-attention mechanisms for image classification tasks. Unlike traditional CNNs, ViT splits images into patches and processes them as sequences, enabling the model to capture global context effectively.

## Objective
- To explore the capabilities of Vision Transformer on the CIFAR-10 dataset.
- To compare its performance with traditional CNN models.
- To implement and evaluate using HuggingFace's Trainer API for improved computational efficiency.

## Methodology
1. **Dataset**: CIFAR-10 (60,000 32x32 images across 10 classes).
2. **Preprocessing**: Data augmentation and patch embedding for input preparation.
3. **Model Architecture**: Implementation of Vision Transformer with patch encoding and positional encoding.
4. **Training**: Leveraged HuggingFace's Trainer API to streamline training and overcome computational limitations.
5. **Evaluation**: Achieved high accuracy through transfer learning and efficient training.

## Results
- **Accuracy**: Reached 98.6% validation accuracy by epoch 3.
- **Efficiency**: Demonstrated the use of pre-trained weights and transfer learning for computationally constrained setups.

## Challenges
Faced computational resource constraints but overcame them using HuggingFace’s Trainer API, reducing the training burden while maintaining accuracy.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/KhushiRajurkar/Vision-Transformer-Image-Classification.git
