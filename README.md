# Analysis of Wellbeing and Lifestyle Parameters on Work-Life Balance
## Overview
This project explores the impacts of various lifestyle factors on work-life balance using a detailed dataset from a public survey. The analysis focuses on how tasks completed, financial security, daily stress, dietary habits, and personal achievements contribute to overall well-being.

## Table of Contents
### 1. Introduction
### 2. Objective
### 3. Methodology
### 4. Data Cleaning and Preparation
### 5. Exploratory Data Analysis
### 6. Regression Analysis
### 7. Results and Discussion
### 8. Conclusions
### 9. How to Use This Repository


## 1. Introduction
In today’s fast-paced environment, achieving a healthy work-life balance is more crucial than ever. This study leverages a comprehensive dataset to assess how daily activities and personal achievements impact individuals' well-being.

## 2. Objective
The primary goal is to quantify the relationships between key lifestyle factors and their collective impact on work-life balance, providing insights into effective strategies for enhancing life quality.

## 3. Methodology
Data Collection
The dataset comprises 15,977 responses from a Kaggle survey, detailing aspects such as task completion, income sufficiency, stress levels, and dietary habits.

Analytical Techniques
Descriptive Statistics: Summarize data distribution and identify anomalies.
Data Cleaning and Preparation: Standardize formats, handle missing values, and convert text to numerical data.
Exploratory Data Analysis (EDA): Use visualizations and regression to understand variable distributions and interrelationships.
Statistical Modeling: Apply multiple linear regression to analyze the impact of lifestyle factors on work-life balance.
Interpretation and Implications: Discuss the real-world applicability of the findings.

## 4. Data Cleaning and Preparation
Python libraries such as Pandas, Matplotlib, and Seaborn were used for data manipulation and visualization. Specific steps included:

	Converting 'DAILY_STRESS' from text to integers.
	Extracting features from the 'Timestamp' data.
	Handling duplicates and missing data to ensure data integrity.

## 5. Exploratory Data Analysis
Visualizations created during the EDA phase helped in understanding the distribution and relationship of the variables. Techniques included:

	Histograms to check normality.
	Scatter plots with regression lines to visualize relationships.
	Bar charts to compare means across groups.

## 6. Regression Analysis
A detailed regression model was built to explore how various factors like task completion and dietary habits influence work-life balance. The model helped quantify the impact of each predictor on the outcome.

## 7. Results and Discussion
The analysis revealed significant relationships between the examined lifestyle factors and work-life balance:

	Completing tasks and sufficient income positively influenced work-life balance.
	Daily stress negatively impacted well-being.
	Healthy eating and personal achievements were strongly correlated with better life satisfaction.

## 8. Conclusions
The findings underscore the importance of comprehensive lifestyle management to enhance work-life balance. Future research could explore additional variables and employ longitudinal data to further validate these results.

## 9. How to Use This Repository
Data Folder: Contains the dataset used in the analyses.
Scripts Folder: Includes all Python scripts for data cleaning, analysis, and visualization.
