ABC Company Employee Data Analysis
A comprehensive data analysis project analyzing employee demographics, team distribution, positions, age groups, and salary patterns for ABC Company.

📊 Project Overview
This project analyzes a dataset of 458 employees across 9 columns to provide detailed insights into the company's workforce structure, salary distribution, and demographic patterns. The analysis includes data preprocessing, exploratory data analysis (EDA), and visualization of key metrics.

🎯 Project Objectives
The analysis aims to answer the following business questions:

Team Distribution Analysis

Count of employees in each team
Percentage distribution of employees across teams
Position Segregation

Distribution of employees across different positions
Position-wise employee count
Age Group Analysis

Identify the predominant age group in the organization
Age distribution patterns
Salary Expenditure Analysis

Identify teams with highest salary spending
Position-wise salary analysis
High-cost team-position combinations
Age-Salary Correlation

Statistical correlation between age and salary
Visual representation of the relationship
📁 Dataset Information
Total Records: 458 rows
Total Features: 9 columns
Company: ABC Company
Dataset Columns
Employee ID
Team
Position
Age
Height (corrected during preprocessing)
Salary
Other demographic information
🔧 Data Preprocessing Steps
1. Data Cleaning
Handling missing values
Checking for duplicate records
Data type conversions
2. Height Column Correction
The height column contained incorrect data. Preprocessing steps included:

# Replace height column with random values between 150 and 180
import numpy as np
df['height'] = np.random.randint(150, 181, size=len(df))
3. Data Validation
Outlier detection
Data consistency checks
Feature engineering (if applicable)
📈 Analysis Performed
1. Team Distribution Analysis
Calculated employee count per team
Computed percentage distribution
Created visualizations (bar charts, pie charts)
2. Position-Based Segregation
Grouped employees by position
Analyzed position distribution
Identified most common positions
3. Age Group Analysis
Created age bins/categories
Identified predominant age groups
Visualized age distribution (histograms, box plots)
4. Salary Expenditure Analysis
Team-wise salary aggregation
Position-wise salary analysis
Combined team-position salary spending
Identified high-cost combinations
5. Age-Salary Correlation
Calculated Pearson correlation coefficient
Created scatter plots with trend lines
Generated heatmaps for correlation matrix

Identify the predominant age group in the organization
Age distribution patterns
Salary Expenditure Analysis

Identify teams with highest salary spending
Position-wise salary analysis
High-cost team-position combinations
Age-Salary Correlation

Statistical correlation between age and salary
Visual representation of the relationship
📁 Dataset Information
Total Records: 458 rows
Total Features: 9 columns
Company: ABC Company
Dataset Columns
Employee ID
Team
Position
Age
Height (corrected during preprocessing)
Salary
Other demographic information
🔧 Data Preprocessing Steps
1. Data Cleaning
Handling missing values
Checking for duplicate records
Data type conversions
