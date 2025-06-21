# Laboratory 2: Data Cleaning and Visualization with the Titanic Dataset  
**Course:** COSC 110 – Introduction to Computing  
**Lab Title:** Basic Data Cleaning and Visualization of Titanic Dataset  

## Objective
This lab introduces simple data cleaning steps and visualizations using Python and Pandas. By the end of the activity, students are expected to:

- Learn how to clean messy data
- Handle missing values, duplicates, and fix incorrect formats
- Prepare a dataset for analysis
- Create basic charts to explore the data

## Dataset
We worked with the Titanic dataset from Kaggle.

- **File used:** `train.csv`  
- The file was loaded into a DataFrame and used throughout the lab.

## Lab Workflow Summary

###  Step 1: Load the Data
- Loaded the dataset using Pandas to start working with the data.

###  Step 2: Understand the Data
- Explored the structure, data types, and basic statistics.
- Looked for columns that might have unexpected formats or values.

###  Step 3: Find Missing Values
- Identified which columns have missing data and how much is missing.

###  Step 4: Handle Missing Data
- Filled in missing values (e.g., with median for numbers).
- Removed columns with too many missing entries.

###  Step 5: Remove Duplicates
- Checked for repeated rows and deleted any duplicates.

### 🏷 Step 6: Fix Data Types
- Converted certain columns (like "Survived" and "Pclass") into categorical data for easier use.

## Basic Visualizations

As part of exploring the data, we created the following charts:

###  1. Bar Plot of Survival Count
- A simple bar chart showing the number of passengers who survived vs. those who didn’t.

###  2. Histogram of Age
- A histogram to visualize how ages are distributed across the passengers.

###  3. Survival by Gender
- A grouped bar chart comparing survival rates between males and females.

## Summary
This lab was all about preparing real-world data for analysis. We cleaned the data, removed problems like duplicates and missing values, and used visualizations to explore patterns. These are useful first steps before doing deeper analysis or modeling.

---

**Author:**  
Aharah Jane Faustino  
