# Titanic Survival Prediction using Machine Learning

Predicting the survival of Titanic passengers using a machine learning model. This project utilizes logistic regression, achieving an accuracy of approximately 77%.

## Table of Contents
- Project Overview
- Dataset Information
- Project Steps
- Results
- Technologies Used
- How to Use
- License

---

## Project Overview

This project analyzes passenger data to predict survival rates using logistic regression. Through data wrangling and feature engineering, the model learns from patterns in the Titanic dataset.

## Dataset Information

The dataset includes passenger details:
- Survived: Survival indicator (1 = Survived, 0 = Did not survive)
- Pclass: Ticket class (1st, 2nd, 3rd)
- Sex: Gender
- Age: Age of the passenger
- SibSp: Number of siblings or spouses aboard
- Parch: Number of parents or children aboard
- Ticket: Ticket number
- Fare: Passenger fare
- Cabin: Cabin number (many missing values)
- Embarked: Port of embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)

## Project Steps

1. **Data Loading and Exploration**: Import and inspect the Titanic dataset for structure and missing values.
2. **Data Analysis and Visualization**:
   - Visualize survival by gender, class, and age using seaborn and matplotlib.
3. **Data Wrangling**:
   - Clean data by handling missing values, dropping irrelevant columns, and encoding categorical data.
4. **Feature Engineering**:
   - Transform features for modeling (e.g., binary encoding for gender and embarked locations).
5. **Model Training**:
   - Split data into training and test sets and train a logistic regression model.
6. **Evaluation**:
   - Evaluate using accuracy, confusion matrix, and classification report.

## Results

- The model achieved a 77% accuracy rate, effectively predicting survival on the Titanic.

## Technologies Used

- Programming Language: Python
- Libraries: pandas, seaborn, scikit-learn, matplotlib
- Platform: Google Colab
- Techniques: Logistic Regression, Data Wrangling, Feature Engineering, Data Visualization

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/titanic-survival-prediction.git
