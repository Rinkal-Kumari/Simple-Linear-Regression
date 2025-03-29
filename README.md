# Simple-Linear-Regression

This project implements a Linear Regression model to predict Salary based on Experience Years. 
The dataset consists of employee data, where each row represents an employee's years of experience
and corresponding salary. The goal is to train a regression model that can predict the salary 
of an employee given their years of experience.

Step 1. We will import the Libraries using Pandas
      The dataset (SalaryPrediction.csv) contains two columns:
        Experience Years: The number of years of work experience.
        Salary: The salary corresponding to that experience.

Step 2. Data Exploration:
We inspect the dataset to check for any missing values, and the dataset contains 40 entries with no missing data.

Step 3. Data Preparation:
The data is split into two parts:
Features (X): The Salary column is used as the input feature.
Target (y): The Experience Years column is the target value for prediction.

Step 4. Train-Test Split:
The dataset is divided into training (70%) and testing (30%) subsets. This helps in evaluating the model's performance after training.

Step 5. Model Selection and Training:
We choose the Linear Regression model from the sklearn library to fit the training data. The model learns the relationship between Salary and Experience Years.

Step 6. Model Prediction:
The trained model is then used to predict Experience Years based on the test set Salary values.

Step 7. Model Evaluation:
The model's performance is evaluated using three metrics:
Mean Absolute Error (MAE): The average difference between predicted and actual values (0.40).
Mean Absolute Percentage Error (MAPE): The average percentage error (12.01%).
Mean Squared Error (MSE): The average squared difference between predicted and actual values (0.23).


   
