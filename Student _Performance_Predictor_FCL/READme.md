🎓 Student Performance Predictor (FCL)

This project implements a Fully Connected Neural Network (Multi-Layer Perceptron) to predict student performance (final score/marks) based on multiple academic and demographic features.

The model achieves 91.44% prediction accuracy.

📌 Project Overview

Task: Predict student performance (regression problem)

Dataset: Student performance dataset (can be adapted from UCI or custom dataset)

Model Type: Fully Connected Neural Network (FCL / MLP)

Evaluation Metric: Mean Absolute Error (MAE)

Performance: 91.44% accuracy (low error on test set)

⚙️ Model Architecture
model = Sequential([
    Dense(64, activation='relu'),
    Dense(64, activation='relu'),
    Dense(64, activation='relu'),
    Dense(32, activation='relu'),
    Dense(1, activation='linear')  # Regression output
])

model.compile(
    optimizer='adam',
    loss='mse',
    metrics=['mae']
)
