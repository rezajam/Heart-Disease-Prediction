# Heart-Disease-Prediction
Heart Disease Prediction

## Overview
This project aims to predict the likelihood of heart disease in patients based on a set of medical features using machine learning algorithms. The dataset used for this analysis is `Heart_disease_dataset.csv`, which contains several features relevant to heart health, such as age, cholesterol levels, chest pain type, and more. The target is a binary outcome indicating whether a patient has heart disease.

## Dataset

The dataset consists of **1190 rows** and **12 columns**, each representing different attributes related to heart disease. Below is a summary of the dataset features:

| Column                 | Description                                        |
|------------------------|----------------------------------------------------|
| `age`                  | Age of the patient (in years)                      |
| `sex`                  | Sex of the patient (1 = male, 0 = female)          |
| `chest pain type`      | Type of chest pain (1 = typical angina, 4 = asymptomatic)|
| `resting bp s`         | Resting blood pressure (in mm Hg)                  |
| `cholesterol`          | Serum cholesterol level (in mg/dl)                 |
| `fasting blood sugar`  | Fasting blood sugar > 120 mg/dl (1 = true; 0 = false)|
| `resting ecg`          | Resting electrocardiographic results (0, 1, 2)     |
| `max heart rate`       | Maximum heart rate achieved                        |
| `exercise angina`      | Exercise-induced angina (1 = yes; 0 = no)          |
| `oldpeak`              | ST depression induced by exercise relative to rest |
| `ST slope`             | The slope of the peak exercise ST segment          |
| `target`               | Target variable (1 = presence of heart disease, 0 = absence of heart disease)|

## Objective

The objective of this project is to build a predictive model that can classify patients into two categories:
- 1: Presence of heart disease.
- 0: Absence of heart disease.

The model will be evaluated on various performance metrics to assess its accuracy and reliability.


### 1. Data Preprocessing
- Handle missing values (if any).
- Normalize and scale features.
- Encode categorical variables (e.g., chest pain type, sex).
- Split the data into training and testing sets.

### 2. Exploratory Data Analysis (EDA)
- Visualize distributions of various features.
- Examine correlations between features and the target.
- Explore feature importance for predicting heart disease.

### 3. Model Training
- Train multiple machine learning models, including:
  - Logistic Regression
  - Decision Tree
  - Random Forest
  - Support Vector Machines (SVM)
  - K-Nearest Neighbors (KNN)

### 4. Model Evaluation
- Evaluate model performance using:
  - Accuracy
  - Precision, Recall, and F1-Score
  - ROC-AUC
  - Confusion Matrix

### 5. Hyperparameter Tuning
- Optimize models using GridSearchCV or RandomizedSearchCV.

## Results

After training, the performance of each model will be evaluated using the following metrics:
- **Accuracy**: Overall performance of the model.
- **Precision & Recall**: Measures of exactness and completeness.
- **F1-Score**: Harmonic mean of precision and recall.
- **ROC-AUC**: Measure of the model's ability to distinguish between classes.

The best-performing model will be used to make predictions on new data.

## Conclusion

This project demonstrates the use of various machine learning algorithms to predict heart disease based on patient data. The results can provide healthcare professionals with a tool to assess the risk of heart disease in patients.

## Future Work

Future improvements could include:
- Testing with more advanced models such as neural networks.
- Performing feature selection to reduce model complexity.
- Gathering additional data to improve model robustness.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.


