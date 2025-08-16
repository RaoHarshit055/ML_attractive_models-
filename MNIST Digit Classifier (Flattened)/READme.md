🧮 MNIST Digit Classifier (FCL)

This project implements a Fully Connected Neural Network (Multi-Layer Perceptron) for handwritten digit classification using the MNIST dataset.
The model achieves 97% test accuracy.

📌 Project Overview

Dataset: MNIST Handwritten Digits (60,000 training, 10,000 test images)

Input: 28×28 grayscale images (flattened to 784 features)

Model: Fully Connected Neural Network (MLP)

Output: 10 classes (digits 0–9)

Accuracy: 97% on test set
Input layer: 784 neurons (28×28 pixels)

⚙️ Model Architecture

Hidden layers:

Dense(64) → ReLU

Dense(32) → ReLU

Output layer: Dense(10) → Softmax

Optimizer: Adam

Loss Function: Categorical Crossentropy

Metrics: Accuracy
