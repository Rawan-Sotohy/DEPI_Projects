# ❤️🔬 Heart Disease Prediction

This project is a machine learning-based pipeline designed to predict the presence of heart disease using clinical features from patient records. It includes data preparation, model training, evaluation.

---

## 📌 Project Objectives

- Build a classification model to predict heart disease.
- Perform proper data preprocessing and handling of missing values.
- Compare multiple ML algorithms and select the best-performing model.
- Save the final model and scaler for deployment.

---

## 🧠 Machine Learning Workflow

1. **Data Cleaning & Preprocessing**
   - Convert labels to binary (`0`: No disease, `1`: Has disease)
   - Remove irrelevant columns
   - Handle missing values

2. **Exploratory Data Analysis (EDA)**
   - Visualize target distribution
   - Analyze feature correlations

3. **Feature Engineering**
   - One-hot encoding for categorical variables
   - Feature scaling using `StandardScaler`

4. **Model Training**
   - Algorithms used:
     - Logistic Regression
     - Random Forest
     - K-Nearest Neighbors
   - Performance evaluated using accuracy, confusion matrix, and classification report

5. **Model Saving**
   - Best model (Random Forest) saved as `.pkl`
   - Scaler also saved for inference pipeline


---


## 📊 Results Summary

* The Random Forest model achieved the highest performance with strong accuracy and balanced metrics.
* Target variable is moderately imbalanced but handled using stratified split.
* The pipeline is ready for integration in a frontend or API.

