# titanic-data-cleaning
“Data cleaning and exploratory analysis of Titanic dataset using Python, Pandas, Matplotlib, and Seaborn.”
# Titanic Data Cleaning & Exploratory Data Analysis (EDA)

## Overview
This project demonstrates how to clean a messy Titanic dataset and perform exploratory data analysis (EDA) using **Python, Pandas, Matplotlib, and Seaborn**.  
The raw dataset included redundant columns (like `zero`, `zero.1`, etc.) and missing values in *Age* and *Embarked*.  
After cleaning, I explored patterns in passenger survival rates across **gender, class, and age**.

---

## Skills & Tools
- Python (Jupyter Notebook)  
- Pandas (data wrangling)  
- Matplotlib & Seaborn (data visualization)  
- Data cleaning (dropping columns, handling missing values)  
- Exploratory Data Analysis (EDA)  

---

## Workflow
1. **Import & Inspect**: Loaded dataset, reviewed structure, and checked missing values.  
2. **Data Cleaning**:  
   - Dropped unnecessary `zero` columns.  
   - Filled missing *Age* with the median.  
   - Filled missing *Embarked* with the most common value.  
3. **Exploratory Data Analysis**:  
   - Distribution of Age and Fare.  
   - Passenger breakdown by class and gender.  
   - Survival rates by gender and class.  
   - Correlation heatmap for numeric features.  
4. **Visualization**: Used histograms, barplots, and heatmaps to highlight trends.  

---

## Key Insights
- Women had significantly higher survival rates than men.  
- First-class passengers survived more often than third-class.  
- Younger passengers (especially children) had better survival chances.  
- About **26% of passengers survived overall**, consistent with the Titanic tragedy.  

---

## 📂 Repository Structure
