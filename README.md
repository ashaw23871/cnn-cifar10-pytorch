GitHub Description:
PyTorch-based CNN for CIFAR-10 image classification featuring data preprocessing, model training, and performance evaluation.

# CNN for CIFAR-10 Image Classification

A Convolutional Neural Network (CNN) implementation using PyTorch for image classification on the CIFAR-10 dataset. This project demonstrates the complete deep learning workflow, including data loading, preprocessing, model creation, training, and evaluation.

## Overview

The CIFAR-10 dataset consists of 60,000 color images belonging to 10 different classes:

- Airplane
- Automobile
- Bird
- Cat
- Deer
- Dog
- Frog
- Horse
- Ship
- Truck

The model uses convolutional layers to automatically extract image features and fully connected layers for classification.

## Features

- CIFAR-10 dataset loading with TorchVision
- Data preprocessing and normalization
- Convolutional Neural Network (CNN) architecture
- ReLU activation functions
- Max Pooling layers
- Adam optimizer
- Cross-Entropy Loss
- Training and evaluation pipeline
- Test accuracy measurement

## Project Structure

```text
CNN_for_CIFAR10.ipynb
```

## Installation

```bash
git clone https://github.com/your-username/cnn-for-cifar10.git
cd cnn-for-cifar10
pip install torch torchvision notebook
```

## Usage

Start Jupyter Notebook:

```bash
jupyter notebook
```

Open:

```text
CNN_for_CIFAR10.ipynb
```

Run all notebook cells to:

1. Download the CIFAR-10 dataset
2. Preprocess the images
3. Build the CNN model
4. Train the network
5. Evaluate performance on the test dataset

## Training Configuration

| Parameter | Value |
|-----------|-------|
| Batch Size | 64 |
| Epochs | 10 |
| Optimizer | Adam |
| Loss Function | CrossEntropyLoss |
| Dataset | CIFAR-10 |

## Technologies Used

- Python
- PyTorch
- TorchVision
- Jupyter Notebook

## Results

The model is evaluated on the CIFAR-10 test dataset after training and reports classification accuracy.

Example Output:

```text
epoch 1/10 -> loss = 1.384464647535168
epoch 2/10 -> loss = 0.9590583133042011
epoch 3/10 -> loss = 0.7797091062111623
epoch 4/10 -> loss = 0.6464850315276314
epoch 5/10 -> loss = 0.5470974202579855
epoch 6/10 -> loss = 0.4570059673979764
epoch 7/10 -> loss = 0.3780814129525743
epoch 8/10 -> loss = 0.2970380445994684
epoch 9/10 -> loss = 0.23991357067795208
epoch 10/10 -> loss = 0.1892690558148467
...
Test Accuracy: 75.91 %
```
