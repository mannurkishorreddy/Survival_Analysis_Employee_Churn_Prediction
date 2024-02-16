# Survival Analysis Employee Churn Prediction

## Project Overview
This project focuses on predicting employee turnover using survival analysis techniques. The goal is to understand when and why employees leave an organization and to identify the factors influencing their decision to churn. The project employs various statistical and machine learning methods tailored for survival analysis, including Kaplan-Meier estimation, Cox Proportional Hazards Model (CoxPH), and Random Survival Forests.

## Data Description
The dataset comprises various employee attributes, including experience, age, gender, industry, profession, salary type (grey wage), and psychological scores (like extraversion, self-control, anxiety, etc.). Each record represents an employee and tracks their duration in the organization and whether they left (event of interest).

## Methodology
The project employs several steps and techniques:
1. **Data Preprocessing**: Cleaning, handling missing values, and transforming categorical variables using one-hot encoding.
2. **Exploratory Data Analysis (EDA)**: Analyzing distributions, unique values, and correlations of features.
3. **Survival Analysis**:
   - **Kaplan-Meier Estimation**: To estimate survival functions and median survival time.
   - **Cox Proportional Hazards Model**: For assessing the impact of various features on the hazard or risk of employee turnover.
   - **Weibull Model**: To analyze the time-to-event data with a parametric approach.
   - **Random Survival Forests**: A non-parametric approach for survival analysis, providing insights into feature importance and survival probabilities.

## Predictive Modeling
The project includes the development of predictive models to estimate the likelihood of employee churn over time. The models are evaluated based on performance metrics like accuracy, AUC-ROC, and concordance index.

## Tools and Libraries
- Python
- Pandas for data manipulation
- NumPy for numerical computations
- Seaborn and Matplotlib for visualization
- Scikit-learn for machine learning models
- Lifelines library for survival analysis

## Conclusion and Insights
The project concludes with key insights into factors leading to employee turnover and provides recommendations on how to improve employee retention. It highlights the importance of certain features and how they contribute to the risk of an employee leaving the organization.
