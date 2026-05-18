# California House Price Prediction using Neural Network

## Overview

This mini project implements house price prediction on the California Housing dataset using an Artificial Neural Network (ANN).

The objective is to predict median house values based on housing features using a regression neural network.

---

## Dataset

Dataset: California Housing Dataset

Features used:

- MedInc (Median Income)
- HouseAge
- AveRooms
- AveBedrms
- Population
- AveOccup
- Latitude
- Longitude

Target Variable:

- Median House Value

---

## Workflow

1. Load California Housing dataset
2. Data preprocessing
3. Feature scaling using StandardScaler
4. Train-test split
5. Build ANN regression model
6. Train model
7. Evaluate performance

---

## Neural Network Architecture

Layers Used:

- Dense Layer
- 2 Hidden Layers with ReLU activation
- Output Layer for Regression

Loss Function:

- Mean Squared Error (MSE)

Optimizer:

- Adam

---

## Technologies Used

- Python
- TensorFlow / Keras
- NumPy
- Pandas
- Scikit-learn
- Matplotlib

---

## Result

Neural network successfully predicts California house prices using regression.

---

## Project Structure

California_House_Price_Prediction/

├── Califronia_house_price.ipynb

└── README.md