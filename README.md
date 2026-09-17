# Hospital Readmission Prediction

## 📌 Overview

This project uses machine learning to predict whether a patient will be **readmitted to the hospital within 30 days** based on patient and hospital-related information.

The project demonstrates a complete machine learning workflow including data preprocessing, categorical feature encoding, model training, and evaluation.

## 🎯 Problem Statement

Hospital readmissions can increase healthcare costs and may indicate that additional follow-up or post-discharge support could be required.

The objective of this project is to build a binary classification model that predicts whether a patient will be readmitted within 30 days.

## 📊 Dataset

The project uses a hospital readmission dataset containing patient and hospital encounter information.

The dataset includes numerical and categorical variables related to:

* Patient demographics
* Hospital encounters
* Diagnoses
* Medications
* Laboratory results
* Previous encounters
* Other clinical and administrative information

### Target Variable

The target represents whether the patient was readmitted within 30 days.

```text
0 → Not readmitted within 30 days
1 → Readmitted within 30 days
```

## 🛠️ Technologies Used

* Python
* Pandas
* NumPy
* Scikit-learn
* Matplotlib
* Seaborn
* Jupyter Notebook / Google Colab

## 🔄 Machine Learning Workflow

```text
Dataset
   ↓
Data Exploration
   ↓
Data Cleaning
   ↓
Feature / Target Separation
   ↓
Train-Test Split
   ↓
Categorical Feature Encoding
   ↓
Model Training
   ↓
Prediction
   ↓
Model Evaluation
```

## 🧹 Data Preprocessing

The dataset contains both numerical and categorical variables.

The preprocessing included:

* Inspecting the dataset
* Handling missing values
* Separating input features and target
* Splitting the data into training and testing sets
* Encoding categorical variables into numerical representations

Categorical variables cannot be directly processed by most traditional machine learning algorithms, so they were transformed into numerical features before model training.

## 🤖 Machine Learning Model

A classification model was trained to predict whether a patient would be readmitted within 30 days.

The model learns patterns from the available patient and hospital information and produces a prediction for unseen patient records.

## 📈 Model Evaluation

The model was evaluated on the test dataset using classification metrics such as:

* Accuracy
* Precision
* Recall
* F1-score
* Confusion Matrix

The evaluation helps determine how effectively the model identifies patients who are and are not readmitted within 30 days.

## 📌 Key Learning Outcomes

* Working with a real-world healthcare dataset
* Handling categorical and numerical features
* Performing categorical feature encoding
* Building a binary classification model
* Evaluating classification performance
* Understanding the limitations of healthcare prediction models

## ⚠️ Limitations

This project is intended for **educational and machine learning practice purposes**.

A model trained on a public dataset should not be treated as a clinical decision-making system. Real-world deployment would require extensive validation, clinical oversight, privacy protections, fairness evaluation, and prospective testing.

## 🚀 Future Improvements

* Compare multiple classification algorithms
* Hyperparameter tuning
* Cross-validation
* Feature selection
* Explainable AI techniques such as SHAP
* Evaluate model performance across different patient groups
* Improve handling of class imbalance if required

## 👩‍💻 Author

**Vidhanshi Upadhyay**
