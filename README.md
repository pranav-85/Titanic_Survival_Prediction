# Titanic Survival Prediction

This project predicts whether a passenger on the Titanic would survive based on features like age, gender, and class, using a Random Forest Classifier.

## Overview
1. **Data Loading**: Load the Titanic dataset.
2. **Data Preprocessing**: Handle missing values, encode categorical features, and drop irrelevant columns.
3. **Model Training**: Use a Random Forest Classifier with hyperparameter tuning via GridSearchCV.
4. **Evaluation**: Evaluate the model's accuracy on the test set.
5. **Prediction**: Predict survival for test data.

## How to Run
1. Install required packages:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
