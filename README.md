# Heart Disease Prediction

## Overview
This project focuses on predicting heart disease using machine learning models. It leverages multiple classification algorithms to identify whether a person has a defective or healthy heart based on medical data.

## Dataset
The dataset used in this project is `heart_disease_data.csv`, which contains various medical parameters. The target variable (`target`) indicates the presence (1) or absence (0) of heart disease.

## Dependencies
To run this project, install the following dependencies:
```bash
pip install numpy pandas scikit-learn xgboost
```

## Steps Involved

### 1. Data Collection and Preprocessing
- Load the dataset using pandas.
- Perform exploratory data analysis (EDA) such as checking missing values, data distribution, and statistical measures.
- Split the dataset into features (X) and target variable (Y).
- Divide the data into training and testing sets using an 80-20 split.

### 2. Model Training and Evaluation
Various machine learning models were trained and evaluated using GridSearchCV to identify the best hyperparameters:
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **XGBoost Classifier**
- **Support Vector Machine (SVM)**
- **K-Nearest Neighbors (KNN)**
- **Gaussian Naive Bayes**
- **Logistic Regression**

#### Hyperparameter Tuning
Each model was fine-tuned using hyperparameter tuning to improve performance.

### 3. Model Performance Evaluation
The models were evaluated using:
- Accuracy score
- Classification report (precision, recall, F1-score)

## Results
The best-performing model and its parameters were identified using GridSearchCV. The classification report for both training and testing sets was printed to assess performance.

## How to Run
1. Clone the repository or download the notebook.
2. Install the dependencies.
3. Run the notebook step by step.

## Future Improvements
- Use feature engineering to improve model performance.
- Implement deep learning models for better accuracy.
- Deploy the model as a web application.
