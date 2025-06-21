# Laboratory 1: Titanic Dataset and Computational Thinking  
**Course:** COSC 110 – Introduction to Computing  
**Lab Title:** Using Python to Explore the Titanic Dataset  

## Objective
The purpose of this lab is to practice computational thinking by working with a real dataset. Students learned how to:

- Break down a problem into smaller parts (Decomposition)
- Spot patterns in data (Pattern Recognition)
- Focus on important details (Abstraction)
- Create step-by-step solutions (Algorithm Design)

I applied these concepts to study survival data from the Titanic.

## Dataset
I used the Titanic dataset from Kaggle.

- **File used:** `titanic.csv`  
- The file was saved in the same directory as the notebook.

## Lab Steps Summary

### Step 1: Decomposition
- Imported libraries like `pandas`
- Loaded the CSV file and used `.head()` to check the data
- Broke the task down into steps like loading and inspecting the data

 **Task:** Describe what steps were needed to load and view the data.

---

### Step 2: Pattern Recognition

**1. Missing Data**
- Used `.isnull().sum()` to find missing values  
- Decided what to do with columns that had missing info

**2. Survival Rate**
- Used `df["Survived"].mean()` to check the survival rate  
- Explained what the result means

**3. Age and Survival**
- Plotted histograms using `matplotlib` to compare survivor vs. non-survivor ages  
- Looked for patterns related to age

 **Task:** For each part above, explain your thought process or write simple logic based on the results.

## Tools Used
- Python 3  
- Pandas  
- Matplotlib  
- Google Colab or Jupyter Notebook  

## Notes
All answers to the questions were written using computational thinking ideas. This lab was a good start for learning how to explore data and make simple predictions.

---

**Author:**  
Aharah Jane Faustino  
