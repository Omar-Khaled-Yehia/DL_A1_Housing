# Housing Price Prediction Model

This project implements a neural network model for predicting housing prices. The model is built using PyTorch and trained on a dataset of housing features to predict the price of houses.

## Overview

The model is designed to take in multiple features as input and outputs the predicted price. The neural network architecture includes:

- Input Layer
- Three Hidden Layers with ELU activations, Batch Normalization, and Dropout for regularization
- Output Layer for the final prediction of housing prices

The model has been optimized for better accuracy while avoiding overfitting using dropout, batch normalization, and appropriate weight initialization techniques.

### Files in this Repository

- `DeepLearning_Assignment1_Final.ipynb`: The main notebook containing the neural network model, training process, and evaluation.
- `README.md`: This file explaining the project, the neural network model, and how to use the notebook.
- `requirements.txt`: List of Python libraries required to run the notebook.

## Model Architecture

The neural network model consists of:

1. **Input Layer**: Takes in the features of the dataset.
2. **Hidden Layer 1**: 64 neurons with Batch Normalization, ELU activation, and Dropout.
3. **Hidden Layer 2**: 32 neurons with Batch Normalization, ELU activation, and Dropout.
4. **Hidden Layer 3**: 16 neurons with Batch Normalization, ELU activation, and Dropout.
5. **Output Layer**: 1 neuron for predicting the housing price.

## Setup Instructions

### Prerequisites

Ensure you have Python 3.x installed on your system. You can install the required libraries by running:

```bash
pip install -r requirements.txt
