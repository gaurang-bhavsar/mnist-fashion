Fashion MNIST Classification with PyTorch ANN (GPU-Accelerated)
A deep learning project implementing an Artificial Neural Network (ANN) to classify fashion items from the Fashion MNIST dataset using PyTorch with GPU acceleration.
🎯 Overview
This project builds a multi-layer fully connected neural network to classify 28x28 grayscale images of 10 different fashion categories including T-shirts, trousers, dresses, coats, sandals, shirts, sneakers, bags, ankle boots, and pullovers.
🏗️ Model Architecture

Input Layer: 784 features (28×28 flattened images)
Hidden Layers:

Layer 1: 512 neurons (ReLU activation)
Layer 2: 256 neurons (ReLU activation)
Layer 3: 128 neurons (ReLU activation)
Layer 4: 64 neurons (ReLU activation)


Output Layer: 10 classes (fashion categories)

📊 Performance

Training Accuracy: 98.79%
Test Accuracy: 89.02%
Dataset: Fashion MNIST (60,000 training images)

🛠️ Technologies

PyTorch (neural network framework)
CUDA (GPU acceleration)
pandas, numpy (data processing)
matplotlib (visualization)
scikit-learn (data splitting)

✨ Features

GPU-accelerated training with CUDA
Custom PyTorch Dataset implementation
Data visualization and exploration
Reproducible results with fixed random seeds
Mini-batch training with DataLoader
Adam optimizer with CrossEntropyLoss

