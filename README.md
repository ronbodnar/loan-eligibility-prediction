# Loan Eligibility Determiniation Prediction Project

## Overview

This project focuses on predicting loan approval outcomes through an extensive analysis of a curated dataset. The predictive model is built using machine learning algorithms, with an emphasis on data exploration, cleaning, and interactive user input.

## Project Structure

- **Notebook:** [`main.ipynb`](main.ipynb) - The Jupyter Notebook containing the entire project, from data exploration to model building and evaluation.

- **Dataset:** [`loan_data.csv`](https://raw.githubusercontent.com/ronbodnar/loan-eligibility-prediction/main/loan_data.csv) - The dataset used for training and testing the predictive model.

## Key Features

- **Data Exploration:** In-depth analysis of the dataset, identifying patterns, correlations, and exploring the impact of various features on loan approval rates.

- **Data Cleaning and Preprocessing:** Proactive handling of missing values, removal of irrelevant columns, and balancing class distribution through oversampling.

- **Model Building:** Implementation of machine learning algorithms, including Logistic Regression, Random Forest Classifier, and Support Vector Classifier.

- **Hyperparameter Tuning:** Precision tuning of the Random Forest Classifier through GridSearchCV, optimizing the model for accuracy.

- **User Interaction:** Development of an interactive UI for real-time user input, allowing individuals to receive transparent loan eligibility predictions.

## Model Performances

- **Logistic Regression:**
  - Accuracy: ~84%
  - Precision: ~85%
  - Recall: ~83%

- **Random Forest Classifier:**
  - Accuracy: ~88%
  - Precision: ~89%
  - Recall: ~88%

- **Support Vector Classifier:**
  - Accuracy: ~81%
  - Precision: ~81%
  - Recall: ~82%

- **Random Forest Classifier (GridSearchCV):**
  - Best Parameters: {'criterion': 'gini', 'max_depth': 10, 'max_features': 'sqrt', 'n_estimators': 500}
  - Best Score: ~86%

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/ronbodnar/loan-eligibility-prediction.git

2. Open and run the Jupyter Notebook main.ipynb using your preferred environment.

3. Explore the project, analyze the code, and interact with the loan eligibility prediction UI.

## License
This project is licensed under the [`MIT License`](LICENSE.md)

Feel free to explore, contribute, and adapt the code for your own projects!
  
