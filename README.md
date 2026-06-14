# Telco Customer Churn Prediction Using Machine Learning Pipeline

## Objective
The objective of this project is to build an end-to-end machine learning pipeline to predict customer churn using the Telco Customer Churn dataset. The project demonstrates data preprocessing, model training, hyperparameter tuning, evaluation, and model deployment preparation.

## Dataset
Telco Customer Churn Dataset

The dataset contains customer information such as:
- Demographics
- Account information
- Services subscribed
- Monthly and total charges
- Churn status

## Technologies Used
- Python
- Pandas
- NumPy
- Scikit-learn
- Matplotlib
- Seaborn
- Joblib
- Google Colab

## Methodology

### 1. Data Preprocessing
- Loaded the dataset
- Handled missing values
- Converted data types
- Removed unnecessary columns
- Encoded categorical variables
- Scaled numerical features

### 2. Machine Learning Pipeline
Implemented preprocessing using:
- Pipeline
- ColumnTransformer
- StandardScaler
- OneHotEncoder

### 3. Models Trained
- Logistic Regression
- Random Forest Classifier

### 4. Hyperparameter Tuning
Used GridSearchCV to find the best Random Forest parameters.

### 5. Model Evaluation
Evaluated models using:
- Accuracy Score
- Classification Report
- Confusion Matrix

### 6. Model Export
The final trained pipeline was exported using Joblib for future use.

## Results
- Successfully built an end-to-end ML pipeline.
- Compared Logistic Regression and Random Forest models.
- Random Forest achieved the best overall performance.
- Saved the trained model as a reusable pipeline.

## Project Files

- Task2_Telco_Churn_Pipeline.ipynb
- telco_churn_pipeline.pkl
- README.md

## Skills Gained
- Machine Learning Pipeline Construction
- Data Preprocessing
- Feature Engineering
- Hyperparameter Tuning
- Model Evaluation
- Model Serialization using Joblib
- Production-Ready ML Workflow

## Author
Abdul Rafaih Mujeeb Abbasi

AI/ML Engineering Internship Task 2
DevelopersHub Corporation
