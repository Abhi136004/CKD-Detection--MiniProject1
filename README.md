
# 🚑 Chronic Kidney Disease (CKD) Detection Using Recurrent Neural Network (RNN)
## 📌 Project Overview
Chronic Kidney Disease (CKD) is a significant health concern linked with conditions such as aging, hypertension, and diabetes. Early detection is vital to reduce life-threatening complications. This project leverages Recurrent Neural Network (RNN) models to predict the presence of CKD using various features such as:

## Demographic Information

Clinical & Laboratory Tests
Urinalysis Results
Medical Conditions (e.g., Proteinuria, Albuminuria)
The dataset contains 680 instances and has been sourced from Kaggle. The goal is to apply deep learning to classify the presence or absence of CKD based on patient data.

## 📊 Dataset Information

->  Source: Kaggle - Chronic Kidney Disease Dataset

->  Size: 680 patient records

## Features:

-> Demographics

-> Clinical values (blood pressure, specific gravity, etc.)

-> Urinalysis

-> Presence of comorbid conditions (e.g., diabetes, hypertension)

-> Target: classification (CKD or not)

# 🧠 Recurrent Neural Network (RNN)
RNN is designed for sequential data and time-series problems. It processes input one step at a time while maintaining a hidden state that captures the context from previous steps, making it suitable for tasks with temporal dependencies.

## RNN Architecture:
-> Input Layer: Accepts patient features at each time step.

-> Hidden Layer: Maintains context using hidden states across time steps.

-> Output Layer: Provides a binary classification (CKD: Yes/No).

