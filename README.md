# Heart Disease Prediction

## Overview:

This project uses machine learning to predict the likelihood of heart disease based on health data, such as age, sex, blood pressure, cholesterol, and chest pain type. The models evaluated include Logistic Regression, K-Nearest Neighbors (KNN), and Random Forest. The goal is to identify which model performs best and which features contribute most to predicting heart disease.

## Dataset:

The dataset used for this project is heart-disease.csv, which contains 303 entries and 14 features, including:

age: Age of the patient

sex: Gender of the patient (1 = male, 0 = female)

cp: Chest pain type

trestbps: Resting blood pressure

chol: Serum cholesterol level

fbs: Fasting blood sugar (1 = greater than 120 mg/dl, 0 = less than 120 mg/dl)

restecg: Resting electrocardiographic results

thalach: Maximum heart rate achieved

exang: Exercise induced angina (1 = yes, 0 = no)

oldpeak: Depression induced by exercise relative to rest

slope: Slope of the peak exercise ST segment

ca: Number of major vessels colored by fluoroscopy

thal: Thalassemia (3 = normal, 6 = fixed defect, 7 = reversible defect)

target: Presence or absence of heart disease (1 = disease, 0 = no disease)

## Data Exploration:

In this step, the dataset is explored to understand the data distribution, missing values, correlations, and relationships between the features. Key visualizations and analyses are performed to gain insights into the data.

The distribution of heart disease is plotted based on gender (sex).

The relationship between age and maximum heart rate is analyzed to observe how they correlate with heart disease.

Chest pain types are visualized to see their impact on heart disease prevalence.

A correlation matrix is created to check the relationships between features and identify the most important ones.

## Modeling:

Three different machine learning models were tested for predicting heart disease:

Logistic Regression

K-Nearest Neighbors (KNN)

Random Forest Classifier

Model Evaluation:
Models were evaluated using accuracy scores and cross-validation.

Data was split into training and validation sets, with training data normalized to improve model performance.

Hyperparameters Tuning:
Hyperparameter optimization was performed using Grid Search and Randomized Search methods to find the best settings for each model.

## Results:

The following accuracy scores were obtained for each model:

Logistic Regression: 83.67%

KNN: 65.31%

Random Forest: 87.76%

Best Performing Model:
Based on the results, the Random Forest Classifier yielded the highest accuracy, making it the best model for this dataset.

## Conclusion:

Best Model: The Random Forest Classifier outperforms the other models with the highest accuracy of 87.76%.

Key Features:

Chest pain type (cp) and maximum heart rate (thalach) were found to be the most strongly correlated with the presence of heart disease.

Age and slope of the peak exercise ST segment also showed significant relationships with heart disease.

This model can be used in healthcare systems to assist in early detection and diagnosis of heart disease based on patient health data.
