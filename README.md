Employee Performance and Retention Analysis
Project Overview

This project aims to analyze employee data and predict both performance and attrition trends using statistical methods, machine learning, and deep learning. The goal is to help organizations make informed decisions about employee retention and performance management.

By leveraging real-world datasets, this project demonstrates data preprocessing, exploratory data analysis (EDA), predictive modeling, and deep learning techniques for HR analytics.

Objective

Analyze employee performance and retention trends.

Identify factors affecting employee attrition.

Predict employee attrition using classification models.

Predict employee performance using regression and deep learning models.

Provide actionable insights to HR departments for employee management.

Dataset

The dataset used in this project (Employee_data.csv) contains the following features:

Feature	Description
EmployeeID	Unique ID for each employee
Name	Employee name
Age	Employee age
Department	Department of the employee
Salary	Employee salary
YearsAtCompany	Total years the employee has worked at the company
PerformanceScore	Performance evaluation score
Attrition	Whether the employee left the company (Yes/No)

The dataset was cleaned and preprocessed to handle missing values, duplicates, and categorical variables.

Project Phases
Phase 1: Data Collection and EDA

Load the dataset using Pandas.

Handle missing values and duplicates.

Perform exploratory data analysis (EDA) with visualization tools like Matplotlib and Seaborn.

Apply probability and statistical analysis:

Calculate probability of attrition based on department and performance.

Apply Bayes’ theorem for attrition prediction.

Perform hypothesis testing to compare performance across departments.

Phase 2: Predictive Modeling

Feature Engineering: Scaling numerical features and encoding categorical variables.

Attrition Prediction: Classification models like Logistic Regression and Random Forest.

Performance Prediction: Regression models like Linear Regression to predict employee performance scores.

Phase 3: Deep Learning

Build a feedforward neural network using TensorFlow/Keras to predict performance scores.

Input features: Age, Salary, Years at Company, Department.

Output: Predicted Performance Score.

Train the model and evaluate with Mean Squared Error (MSE).

Libraries Used

Pandas

NumPy

Matplotlib

Seaborn

Scikit-learn

TensorFlow / Keras

How to Run

Clone the repository:

git clone https://github.com/YourUsername/Employee-Performance-Retention-Analysis.git


Install dependencies:

pip install -r requirements.txt


Open the Jupyter Notebook Employee_Performance_Retention.ipynb and run all cells.

Ensure the dataset Employee_data.csv is in the same folder as the notebook.

Results

Visual insights on employee performance and attrition trends.

Confusion matrix and metrics for attrition prediction model.

R² Score and MSE for performance prediction models.

Neural network performance with training and validation loss plots.

Conclusion

This project provides an end-to-end analysis of employee performance and retention using statistical, machine learning, and deep learning techniques. It helps HR departments understand key factors affecting attrition and supports data-driven decision-making for workforce management.

Author

Komal Kushwaha

GitHub: https://github.com/Komal3114

LinkedIn: https://www.linkedin.com/in/komal-kushwaha-datascientist/         
