# Customer Churn Prediction

## Overview
This project focuses on predicting customer churn for a subscription-based streaming service. The goal is to build a predictive model using **Decision Trees** and **Random Forests** to identify customers who are likely to cancel their subscriptions.

## Dataset
The dataset includes customer attributes such as:
- **Demographics**: Age, Location, Subscription Length
- **Usage Behavior**: Watch Time, Number of Logins, Preferred Content Type
- **Subscription Details**: Membership Type, Payment Method, Payment Issues
- **Customer Support Interactions**: Number of Complaints, Resolution Time

## Project Workflow
1. **Data Collection & Preparation**
   - Cleaning and preprocessing the dataset
   - Handling missing values and feature selection

2. **Exploratory Data Analysis (EDA)**
   - Identifying trends and patterns in customer behavior
   - Visualizing key churn indicators

3. **Model Development**
   - Implementing a **Decision Tree Classifier**
   - Enhancing accuracy using **Random Forests**
   - Hyperparameter tuning for improved performance

4. **Model Evaluation**
   - Accuracy, Precision, Recall, F1 Score, and Confusion Matrix
   - Comparison between Decision Tree and Random Forest models

5. **Business Insights & Recommendations**
   - Identifying key factors contributing to churn
   - Actionable strategies to improve customer retention

## Installation
To run this project, install the required dependencies:
```bash
pip install pandas numpy scikit-learn matplotlib seaborn
```

## Usage
Run the Python script or Jupyter Notebook to execute the churn prediction model.
```bash
python churn_prediction.py
```

## Results & Insights
- Random Forest outperformed Decision Tree in accuracy and generalization.
- Key factors affecting churn include payment issues and low engagement levels.
- Business recommendations include targeted retention strategies for at-risk customers.

## Author
[**Mohammad Adas**](https://github.com/mohammad-adas)
