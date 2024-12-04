# Few-Shot Federated Learning

This project explores **Few-Shot Learning** in a **Federated Learning** setup, where models are trained across multiple clients (with limited data per class) while keeping the data on the clients for privacy. The goal is to develop a model that can learn from a small amount of data in a federated environment and still make accurate predictions.

## Technologies Used
- **PyTorch**: For implementing machine learning models using neural networks with layers like Max Pooling and ReLU activation functions.
- **Federated Learning**: A decentralized learning method that allows clients to train their models on local data without sharing it.
- **Few-Shot Learning**: An approach to machine learning where the model can learn effectively from only a few examples of each class.
- **PyTorch Geometric**: For implementing graph neural networks and experimenting with graph-based data and node classification tasks.
- **CIFAR-10 Dataset**: A benchmark dataset used to evaluate model performance in a federated setup.
- **Weighted Binary Cross-Entropy Loss**: A custom loss function designed to address class imbalance by assigning weights based on the number of samples per class.

## Features
- **Federated Setup**: The project simulates a federated environment with multiple clients, each holding a portion of the CIFAR-10 dataset.
- **Few-Shot Learning**: Implements strategies to train models with very few examples per class, addressing the challenge of limited data.
- **Model Evaluation**: Models are evaluated using performance metrics like accuracy, precision, and recall, taking into account class imbalance.

## Installation
To run the project, follow these steps:

1. Clone the repository:
   ```bash
   git clone https://github.com/LavishGupta613/Few-Shot-Federated-Learning.git
