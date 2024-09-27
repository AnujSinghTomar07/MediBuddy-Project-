# MediBuddy Capstone Project

## Introduction

MediBuddy is a leading digital healthcare platform in India, offering a wide range of services including inpatient hospitalization, outpatient services, and corporate wellness benefits. Founded in 2000 and headquartered in Bangalore, Karnataka, India, MediBuddy is known for its innovative technology platform that streamlines the process of accessing and utilizing health benefits.

## Objective 

The primary objective of this project is to analyze key factors influencing insurance claims and policy costs for MediBuddy. The analysis aims to provide actionable insights on whether certain demographics or health-related factors should influence policy decisions. Additionally, the project involves building a predictive machine learning model to estimate the amount spent on each policy with the highest possible accuracy.

## Datasets

The project utilizes two datasets:

- **Pre-Health Checkup Dataset**: Contains information on age and BMI (Body Mass Index) from pre-health checkups conducted before policy coverage.
- **Personal Details Dataset**: Includes personal attributes such as the number of children, smoking status, geographic location, and gender.

## Key Analyses and Questions

- **Gender Impact**: Analyze whether gender plays a role as a constraint for MediBuddy when extending policies.
- **Average Policy Costs**: Calculate the average amount of money spent on each policy cover.
- **Geographic Location**: Examine if different policies should be offered based on geographic location.
- **Dependents Analysis**: Determine if the number of dependents influences the amount claimed on insurance policies.
- **BMI Analysis**: Investigate if BMI can predict insurance claim amounts and provide insights for policy extensions.
- **Smoking Status**: Assess the importance of smoking status in determining policy costs.
- **Age Analysis**: Explore if age affects insurance claims and if older individuals tend to have higher claim amounts.
- **Health-Based Discounts**: Provide recommendations on offering discounts based on health status (BMI).

## Methodology

1. **Data Preprocessing**: Clean and preprocess the datasets, handling missing data, outliers, and inconsistencies. Perform feature engineering to extract relevant features.
2. **Exploratory Data Analysis (EDA)**: Conduct exploratory analysis to identify patterns and trends. Use visualizations to understand relationships between variables.
3. **Feature Selection**: Select the most relevant features impacting insurance policy costs and claims.
4. **Machine Learning Model**: Build and train a machine learning model using algorithms such as linear regression, decision trees, and random forests.
5. **Model Optimization**: Perform hyperparameter tuning and validation to improve model performance.
6. **Model Evaluation**: Evaluate the model using metrics like Mean Absolute Error (MAE), Root Mean Squared Error (RMSE), and R-squared.

## Tools and Technologies

- **Python**: For data manipulation, analysis, and machine learning.
- **Pandas and NumPy**: For data preprocessing and manipulation.
- **Matplotlib and Seaborn**: For data visualization.
- **Scikit-Learn**: For machine learning model development and evaluation.
- **Power BI**: For interactive visualizations and presenting insights.

## Expected Outcomes

- **Insights**: Detailed insights into factors affecting insurance claims and policy costs, including gender, geographic location, dependents, BMI, smoking status, and age.
- **Predictive Model**: A model that accurately estimates the amount spent on policies to assist in decision-making.
- **Recommendations**: Recommendations on offering differentiated policies based on location, health status, and potential discounts based on BMI or other health indicators.

This project aims to provide a comprehensive analysis of the factors affecting insurance policies and claims, enabling MediBuddy to make data-driven decisions and optimize their offerings for different customer segments.

