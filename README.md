# NeuralNetworksforImageRecognition

## Overview
This repository showcases a comprehensive project on image recognition and object classification using neural networks and classical computer vision techniques. The project utilizes the CIFAR-10 dataset to implement and compare different machine learning algorithms, focusing on the extraction of meaningful features from images and training a multilayer Artificial Neural Network (ANN).

## Project Objectives
- **Feature Extraction**: Utilize classical computer vision techniques to extract relevant features from raw images.
- **Model Training**: Implement a multilayer ANN from scratch to classify objects within images.
- **Performance Evaluation**: Assess the accuracy, precision, and recall of the models across different configurations and datasets.

## Project Pipeline
The project is divided into two main parts:

### Part I: Implementation and Evaluation on CIFAR-10
1. **Data Loading**: Download and load the CIFAR-10 dataset.
2. **Feature Extraction**: Use feature detectors and descriptors, including:
   - Wavelet
   - HOG
   - MinEigen with Block
   - MinEigen with SIFT
   - Harris with Block
   - Harris with SIFT
   - MSER with Block
   - MSER with SIFT
3. **Model Development**: Implement a multilayer ANN and evaluate its performance on training and validation datasets.
4. **Reporting**: Provide metrics including accuracy, precision, and recall.

### Part II: Advanced Classification
1. **Challenging Dataset**: Identify and utilize a more complex image classification dataset (e.g., CIFAR-100 or a dataset from ImageNet).
2. **Model Optimization**: Experiment with various architectures, including different layer sizes and numbers of layers.
3. **Performance Metrics**: Report the accuracy, precision, and recall for different configurations.

## Deliverables
- Python Notebooks for each implementation and model configuration.
- A project report summarizing performance metrics and insights.

## Technologies Used
- Python
- TensorFlow/Keras or PyTorch
- OpenCV
- NumPy
- Matplotlib

## Getting Started
To run the code and replicate the results, follow these steps:

1. Clone this repository:
   ```bash
   git clone https://github.com/zanbam/NeuralNetworksforImageRecognition.git