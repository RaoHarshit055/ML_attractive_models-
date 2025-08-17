Loan Defaulter Prediction Model
📌 Project Overview

This project predicts whether a loan applicant is likely to default on their loan or not, based on financial and demographic data. The model is built using a Sequential Neural Network (Keras/TensorFlow) and evaluates predictions using accuracy, confusion matrix, and other metrics.

The goal is to help banks and financial institutions assess loan risk more effectively.

📂 Dataset

Contains applicant details such as:
Employment status
Bank balance
Annual income
Target column: Loan Default (Yes/No)

⚙️ Tech Stack

Python
TensorFlow / Keras (Neural Network Model)
Pandas & NumPy (Data Processing)
Matplotlib & Seaborn (Visualization)
Scikit-learn (Preprocessing, Evaluation Metrics)

🏗️ Model Architecture

The model is built using a Sequential API with:
Dense hidden layers (ReLU activation)
Output layer with Sigmoid activation (for binary classification)
Loss function: Binary Crossentropy
Optimizer: Adam
