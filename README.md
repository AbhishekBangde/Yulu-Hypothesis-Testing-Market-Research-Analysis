# Yulu-Hypothesis-Testing-Market-Research-Analysis

🚲 Yulu Business Case – Hypothesis Testing Analysis
📌 Project Overview

Yulu is India’s leading micro-mobility service provider offering electric cycles for first- and last-mile connectivity.
This project applies statistical hypothesis testing to analyze how working days, weather conditions, and seasons impact electric cycle rental demand.

The goal is to generate data-driven insights that help optimize Yulu’s operational and seasonal planning strategies.

🎯 Business Objectives

Analyze whether working days influence electric cycle rentals

Evaluate the impact of weather conditions on rental demand

Examine how seasons affect the number of rentals

Identify the dependency between weather and seasons

Provide actionable business recommendations based on statistical results

📂 Repository Structure
Yulu-Hypothesis-Testing/
│
├── Business_Case_Yulu_Hypothesis_Testing.ipynb

File Details

Business_Case_Yulu_Hypothesis_Testing.ipynb
Contains the complete analysis including data preprocessing, exploratory data analysis, assumption testing, hypothesis testing, and business recommendations.

📊 Dataset Description

The dataset consists of 10,886 hourly records with the following variables:

datetime – Date and time of rental

season – Spring, Summer, Fall, Winter

holiday – Holiday indicator

workingday – Working day indicator

weather – Weather condition category

temp – Temperature (°C)

atemp – Feels-like temperature (°C)

humidity – Humidity level

windspeed – Wind speed

casual – Casual user rentals

registered – Registered user rentals

count – Total rentals

🔍 Methodology

Data Cleaning & Validation

Checked for missing values and duplicates

Converted data types and encoded categorical variables

Exploratory Data Analysis (EDA)

Univariate analysis for continuous and categorical variables

Bivariate analysis between demand and key influencing factors

Statistical Testing

Normality and variance assumption checks

Applied appropriate hypothesis tests based on data distribution

🧪 Hypothesis Tests Performed
Business Question	Statistical Test
Effect of working day on rentals	Two-Sample t-Test
Effect of weather on rentals	Kruskal-Wallis Test
Effect of season on rentals	Kruskal-Wallis Test
Weather vs season dependency	Chi-Square Test
✅ Key Findings

Working days do not have a significant impact on rental demand

Rental demand varies significantly across weather conditions

Rental demand differs significantly across seasons

Weather conditions are dependent on seasons

💡 Business Recommendations

Maintain consistent operational planning across weekdays and weekends

Increase bicycle availability during favorable weather conditions

Allocate additional resources during high-demand seasons

Align seasonal strategies with expected weather patterns

🛠 Tools & Technologies Used

Python

Pandas, NumPy

Matplotlib, Seaborn

SciPy

Statsmodels

📌 Conclusion

This project demonstrates the practical application of hypothesis testing and statistical analysis to solve a real-world business problem. The insights derived can help Yulu improve demand forecasting, operational efficiency, and strategic planning.
