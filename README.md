# Graduation_admission_usingANN
## Admission Prediction Using Neural Networks

This project predicts the **chances of admission** for a graduate program based on students' academic profiles using
a **regression-based neural network** built with TensorFlow and Keras.

## Problem Statement

Given a dataset of student profiles, the goal is to predict the `Chance of Admit` (a float between 0 and 1) based on features like:
- GRE Score
- TOEFL Score
- University Rating
- Statement of Purpose (SOP)
- Letter of Recommendation (LOR)
- CGPA
- Research Experience

## Machine Learning Approach

- **Model Type:** Neural Network (Regression)
- **Libraries Used:**  
  - TensorFlow / Keras  
  - Scikit-learn  
  - Pandas, NumPy, Matplotlib
- **Data Preprocessing:**  
  - Removed `Serial No.` column  
  - Scaled features using `MinMaxScaler` (also tested with `StandardScaler`)
- **Architecture:**
  - Input Layer: 7 features
  - Hidden Layers: Dense layers with ReLU activation
  - Output Layer: Single neuron with linear activation (regression)


##  Evaluation Metrics

Since it's a **regression task**, we used:

- **Mean Absolute Error (MAE)**
- **Mean Squared Error (MSE)**
- Accuracy is **not** used, as it's not suitable for regression.

---
