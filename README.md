# Healthcare Insurance Charges Prediction Project

## Overview
This project aims to build a predictive model for healthcare insurance charges using statistical analysis and machine learning techniques. The model predicts insurance costs based on various demographic and lifestyle factors such as age, sex, BMI, smoker status, number of children, and region. The goal is to develop an accurate and interpretable model that can assist insurance companies in estimating charges for potential customers and individuals in understanding the factors influencing insurance costs.

## Methodology
1. Data Collection: Utilized a dataset containing information about individuals' demographics, lifestyle, and insurance charges.
2. Data Preprocessing: Cleaned and prepared the dataset for analysis by handling missing values, converting categorical variables into numerical format, and splitting the data into training and testing sets.
3. Exploratory Data Analysis (EDA): Explored the dataset to gain insights into variable relationships, identify patterns, and understand the distribution of insurance charges.
4. Model Building: Developed a predictive model using linear regression to predict insurance charges based on the available features.
5. Model Evaluation: Evaluated the model's performance using metrics such as R-squared and root mean squared error (RMSE) to assess prediction accuracy.
6. Model Interpretation: Examined the coefficients of the model to understand the impact of different factors on insurance charges.
7. Visualization: Created visualizations, such as scatter plots of residuals, to further analyze the model's performance and understand the relationship between actual and predicted charges.

## Goal
The primary goal of this project is to create a reliable predictive model that can assist both insurance companies and individuals in estimating healthcare insurance charges. By understanding the factors influencing insurance costs, individuals can make informed decisions about their healthcare coverage, while insurance companies can improve pricing strategies and risk assessment. Additionally, the insights gained from this analysis can contribute to discussions about healthcare policy and affordability.

## Hypothesis Testing and Statistical Analysis
1. Two-Sample t-test: The two-sample t-test is a statistical test used to determine if the means of two independent groups are significantly different from each other. In the context of this project, the two-sample t-test can be applied to compare the average healthcare insurance charges between two groups, such as smokers and non-smokers. By conducting this test, we can assess whether there is a significant difference in insurance charges based on smoking status.
2. Chi-Square test: The chi-square test is a statistical test used to determine if there is a significant association between two categorical variables. In this project, the chi-square test can be applied to analyze the relationship between two categorical variables, such as region and smoker status. By conducting this test, we can assess whether there is a significant association between the region where an individual resides and their smoking behavior.
3. ANOVA test (Analysis of Variance): The ANOVA test is a statistical test used to determine if there are statistically significant differences between the means of three or more independent groups. In the context of this project, the ANOVA test can be applied to analyze the differences in healthcare insurance charges among individuals from different regions. By conducting this test, we can assess whether there are significant variations in insurance charges based on geographic location.

## Dataset Description
1. Age: Integer indicating the age of the primary beneficiary(excluding those above 64yrs, since they are generally covered by the government).
2. Sex: Policy holder's gender, either male or female.
3. BMI: Body Mass Index, which provides a sense of how over or under-weight a person is relative to their height. BMI is equal to weight (in kg) divided by height (in metres) squared. An ideal BMI is within the range of 18.5 to 24.9. 
