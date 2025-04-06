# Diabetes Detection ML Project

## Overview
This project is a machine learning model that predicts whether a person has diabetes based on various health factors. It uses the **Pandas** library for data handling, **Scikit-learn** for building and evaluating the model, and **Logistic Regression** for classification.

## Dataset
The dataset contains information about:
- Pregnancies
- Glucose levels
- Blood pressure
- Skin thickness
- Insulin levels
- Diabetes pedigree function
- Weight and age group categories
- Gender

### Model Details:
- **Algorithm used**: Logistic Regression
- **Evaluation metric**: Precision, Recall, F1-Score

## Results
The model was evaluated on a test set, and the following metrics were obtained:

- **Accuracy**: 79%
- **Precision** (class 0 - No Diabetes): 0.80
- **Precision** (class 1 - Diabetes): 0.77
- **Recall** (class 0 - No Diabetes): 0.85
- **Recall** (class 1 - Diabetes): 0.70
- **F1-Score** (class 0 - No Diabetes): 0.82
- **F1-Score** (class 1 - Diabetes): 0.73

### Confusion Matrix
- Class 0 (No Diabetes): 
  - Precision: 0.80
  - Recall: 0.85
- Class 1 (Diabetes): 
  - Precision: 0.77
  - Recall: 0.70

## Libraries Used
- **Pandas**: Data manipulation and analysis
- **NumPy**: Numerical computations
- **Scikit-learn**: Machine learning and model evaluation

## How to Run
1. Clone the repository:
   ```bash
   git clone https://github.com/IbrahimHashhash/diabetes-detection-ml.git
