# Dry Eye Detection using Machine Learning

This project aims to detect **Dry Eye Disease** using machine learning techniques. The model is trained on medical data to predict whether a patient has Dry Eye Disease based on certain features.

## **Project Overview**

- **Goal**: Develop a machine learning model to predict the presence of Dry Eye Disease.
- **Technologies Used**:
  - Python
  - Pandas
  - NumPy
  - Scikit-learn
  - Matplotlib
  - Seaborn
  - SHAP (for model explainability)
  - Flask (for creating a web application interface)
- **Dataset**: The project uses a medical dataset (`data/Dry_Eye_Dataset.csv`) containing features related to eye health to train the model.

## **How It Works :**

-Data Preprocessing:The dataset is cleaned and processed to handle missing values and outliers.

-Feature Selection: Key features from the dataset are selected for model training.

-Model Training: Machine learning algorithms such as Logistic Regression, Random Forest, etc., are used to build the model
.
-Evaluation: The model is tested on unseen data, and metrics like accuracy, precision, and recall are calculated.

-Model Explainability: SHAP is used to explain model predictions.


## **Key Features :**
-Predicts whether a patient has Dry Eye Disease based on various medical features.

-Built using machine learning techniques like classification.

-Includes visualizations of model performance and data insights.

-Model explainability with SHAP values for better understanding of predictions.

-Flask API to deploy the model and make predictions through a web interface.


## **Results :**
The machine learning model achieved an accuracy of XX% in detecting Dry Eye Disease based on the dataset.

Evaluation metrics like accuracy, precision, recall, and F1-score are reported in the notebook.


**Files and Directories :**
data/: Contains the dataset (Dry_Eye_Dataset.csv) for Dry Eye Disease detection.

ml-dry-eye-disease.ipynb: Jupyter notebook with code for data analysis, model training, and evaluation.

best_model.pkl: The trained machine learning model, ready for prediction.

app.py: Flask application for web interface deployment.

requirements.txt: List of dependencies required to run the project.


**Contact :**
Author: Khushi Atara
Email: khushiatara04@gmail.com


