# Credit Card Churn Prediction using Artificial Neural Networks

## Project Overview
This project implements a production-style Artificial Neural Network (ANN) pipeline to predict customer churn in a banking environment.

Customer churn prediction is a high-impact business problem. Retaining existing customers is significantly more cost-effective than acquiring new ones. This model helps identify customers who are likely to leave, enabling proactive retention strategies.

Final Model Test Accuracy: 84%

---

## Business Problem
Banks collect extensive customer data including demographics, account activity, and financial behavior. The objective is to predict:

Will a customer churn (1) or stay (0)?

Accurate prediction enables:

* Targeted retention campaigns
* Personalized offers
* Risk-based customer segmentation

---

## Dataset Features

The model was trained on features such as:

* Credit Score
* Geography
* Gender
* Age
* Tenure
* Balance
* Number of Products
* Has Credit Card
* Is Active Member
* Estimated Salary

Target Variable:

* Exited (0 = Stayed, 1 = Churned)

---

## Machine Learning Pipeline

1. Data Cleaning
2. Label Encoding & One-Hot Encoding
3. Feature Scaling using StandardScaler
4. Train-Test Split
5. ANN Model Design
6. Model Training
7. Performance Evaluation

---

## Model Architecture

Model 1

* Input Layer
* Dense Layer (Sigmoid)
* Output Layer (Sigmoid)

Loss Function: Binary Crossentropy
Optimizer: Adam
Evaluation Metric: Accuracy

Model 2

* Input Layer
* Dense Layer (Sigmoid)
* Dense Layer (Sigmoid)
* Output Layer (Sigmoid)

Loss Function: Binary Crossentropy
Optimizer: Adam
Evaluation Metric: Accuracy

---
