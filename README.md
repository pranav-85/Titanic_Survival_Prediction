# Titanic Survival Prediction

This project aims to predict whether a passenger on the Titanic would survive or not, based on various features like age, gender, and passenger class. We use machine learning, specifically a Random Forest Classifier, to make these predictions.

## Steps Involved

1. **Data Loading**: We load the Titanic dataset using `pandas`.
2. **Data Exploration**: Basic exploration is done to understand the data, like checking for missing values and visualizing correlations.
3. **Data Preprocessing**:
   - Impute missing ages with the mean.
   - One-hot encode categorical features like `Embarked` and `Sex`.
   - Drop irrelevant columns like `Name`, `Ticket`, and `Cabin`.
4. **Train-Test Split**: We split the data into training and test sets using stratified sampling to ensure balanced classes.
5. **Modeling**:
   - We use a pipeline that handles data preprocessing and modeling.
   - The Random Forest model is trained,
