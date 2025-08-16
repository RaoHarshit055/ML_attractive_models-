❤️ Heart Disease Prediction (FCL)

This project implements a Fully Connected Neural Network (Multi-Layer Perceptron) for heart disease prediction based on clinical and demographic features.

The model achieves 98.53% accuracy with excellent precision, recall
📌 Project Overview

Task: Binary classification → Predict if a person has heart disease

Dataset: Heart Disease Dataset (UCI / Kaggle)

Model Type: Fully Connected Neural Network (FCL / MLP)

Evaluation Metrics: Accuracy, Precision, Recall, F1-score, ROC-AUC

Performance:

Accuracy: 98.53%

Precision: 1.0

Recall: 0.97

F1-Score: 0.985

ROC-AUC: 0.995

⚙️ Model Architecture
model = Sequential([
    Dense(64, activation='relu'),
    Dense(32, activation='relu'),
    Dense(8, activation='relu'),
    Dense(1, activation='sigmoid')  # Binary output
])

model.compile(
    optimizer='adam',
    loss='BinaryCrossentropy',
    metrics=['accuracy']
)
