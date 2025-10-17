# Bank Customer Churn Prediction using Artificial Neural Network
## Project Overview
This project implements an Artificial Neural Network (ANN) to predict bank customer churn. The model analyzes customer data to determine whether a customer is likely to leave the bank, helping financial institutions take proactive measures for customer retention.

## Problem Statement
Banks face significant challenges with customer retention. Identifying customers who are likely to churn (leave the bank) allows for targeted retention strategies, reducing customer acquisition costs and maintaining revenue streams.

## Dataset
The project uses the Churn_Modelling.csv dataset containing customer information including:

Demographics: Geography, Gender, Age

Financial Details: Credit Score, Balance, Estimated Salary

Banking Relationship: Tenure, Number of Products

Service Usage: Has Credit Card, Is Active Member

Target Variable: Exited (1 if customer left, 0 if retained)

## Technical Implementation
## Data Preprocessing
Encoding Categorical Data:

Label Encoding for "Gender" column

One-Hot Encoding for "Geography" column

Feature Scaling: Applied StandardScaler for normalization

Train-Test Split: 80-20 split with random state for reproducibility

## Neural Network Architecture
Framework: TensorFlow/Keras

Model Type: Sequential ANN

Layers:

Input layer + First hidden layer: 6 neurons, ReLU activation, He uniform initialization

Second hidden layer: 6 neurons, ReLU activation, He uniform initialization

Output layer: 1 neuron, Sigmoid activation, Glorot uniform initialization

## Model Training
Optimizer: Adam

Loss Function: Binary Crossentropy

Metrics: Accuracy

Training: 100 epochs with batch size of 32

## Results
The model achieves high accuracy in predicting customer churn, enabling banks to:

Identify at-risk customers

Implement targeted retention campaigns

Optimize customer service resources

## Key Features
End-to-end ML pipeline: From data preprocessing to model evaluation

Scalable architecture: Easy to modify for different datasets

Production-ready: Includes single prediction functionality

Comprehensive evaluation: Confusion matrix and accuracy metrics

## Usage
The notebook demonstrates:

Data loading and exploration

Data preprocessing pipeline

Neural network construction

Model training and evaluation

Single prediction capability

Performance metrics calculation

## Requirements
Python 3.x

TensorFlow

pandas

numpy

scikit-learn

## Future Enhancements
Hyperparameter tuning

Cross-validation

Feature importance analysis

Deployment as a web service

This project serves as a comprehensive example of applying deep learning to real-world business problems in the banking sector.

## Accuracy Acheived
<img width="136" height="74" alt="image" src="https://github.com/user-attachments/assets/c40597ab-f9e5-4d76-a46e-8b0ddfbfbd42" />

