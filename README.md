# Salary Data Analysis Project

## Overview

This project analyzes a comprehensive salary dataset to identify patterns and demographic factors that influence compensation. Through exploratory data analysis and visualization, we examine how gender, age, education level, job title, and years of experience affect salary outcomes.

## Dataset

Dataset from Kaggle: https://www.kaggle.com/datasets/mohithsairamreddy/salary-data , the dataset (`Salary_Data.csv`) contains information about professionals across various industries, including:

- Age
- Gender
- Education Level
- Job Title
- Years of Experience
- Salary

## Key Questions Explored

1. How does gender affect salary across different industries and roles?
2. What is the relationship between education level and compensation?
3. How much does work experience impact earning potential?
4. Which job titles and roles command the highest salaries?
5. Is there a significant gender pay gap, and how does it vary by other factors?

## Analysis Approach

The analysis is performed using Python with libraries such as pandas, matplotlib, seaborn, and scikit-learn. The workflow includes:

1. **Data Loading & Cleaning**: Handling missing values, removing outliers, and preparing the dataset for analysis.
2. **Exploratory Data Analysis (EDA)**: Creating visualizations to understand distributions and relationships.
3. **Demographic Analysis**: Breaking down salary data by gender, age, education, and experience.
4. **Gender Pay Gap Analysis**: Quantifying salary disparities between genders across different segments.
5. **Regression Analysis**: Building models to predict salary based on various factors.

## Key Findings

- Higher education levels correlate with significantly higher salaries
- Years of experience is the strongest predictor of salary
- There exists a gender pay gap that varies across education levels and job types
- Technical and management roles typically command higher compensation

## Requirements

- Python 3.7+
- Jupyter Notebook
- pandas
- numpy
- matplotlib
- seaborn
- scikit-learn

## How to Run

1. Clone this repository
2. Ensure all required packages are installed: `pip install -r requirements.txt`
3. Open and run the Jupyter Notebook: `Salary_Analysis.ipynb`

## Future Work

- Incorporate industry-specific analysis
- Add geographic salary variations if data becomes available
- Develop interactive visualizations
