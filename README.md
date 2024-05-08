# Project Title: Predicting Employee Attrition

## Overview

This project aims to analyze employee attrition data to identify factors contributing to employee turnover. 
The analysis includes data preprocessing, exploratory data analysis (EDA), and model development to predict employee attrition based on various factors such as age, income, years in the current role, and more.

### Prerequisites

pip install -r requirements.txt

### Installation

1. Clone the repository
2. Navigate to the project directory
3. Create a virtual environment - python -m venv venv source venv/bin/activate (macOS)
4. Install the required packages

## Usage

1. Load the dataset
2. Perform data preprocessing:
   - Handle missing values
   - Encode categorical variables
   - Standardize numerical features
3.Explore the data using the EDA:
   - Analyze factors contributing to attrition
   - Visualize the data using line plots and pie charts outputs
4.Develop and evaluate models to predict attrition:
   - Split the data into training and testing sets
   - Implement grid search to find the best model and parameters
   - Evaluate the model using accuracy, precision, recall, and F1 score and display the best results.
     
## Additional Notes

- The project includes scripts for data preprocessing, EDA, and model development.
- The `requirements.txt` file lists all the Python packages required for the project.
- The project uses Scikit-learn for machine learning tasks and Plotly for data visualization.
- The dataset used in this project is the "IBM HR Analytics Employee Attrition & Performance" dataset from the Kaggle.
