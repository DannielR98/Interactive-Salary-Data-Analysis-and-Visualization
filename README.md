# Salary Analysis in Python

## Overview
This project analyzes salary data based on various factors such as age, gender, education level, job title, and years of experience. The dataset comes from Kaggle, and the analysis includes data preprocessing, missing value imputation, and salary trends visualization.

## Dataset
The dataset used in this analysis is located at: /kaggle/input/salary-analysis/Salary_Data.csv

### Features: 
- `Age`: Age of the individual
-  `Gender`: Gender identity
-  `Education Level`: Highest attained education
-  `Job Title`: The individual's job title
-  `Years of Experience`: Total years of experience in the workforce
-  `Salary`: Annual salary in USD ## Libraries Used This analysis leverages various Python libraries, including:
-  `numpy`: Linear algebra operations
-  `pandas`: Data manipulation and CSV handling
-   `matplotlib.pyplot` & `seaborn`: Data visualization
-  `plotly.express`: Interactive plots
  
  
## Data Processing
1. **Reading the data**: Loaded via `pandas`
2. **Handling missing values**:
   - Imputed missing salaries using the mean salary for each job title
   - Remaining missing values were filled with the overall mean salary
3. **Exploratory Data Analysis (EDA)**:
   - Median age and mean salary calculated
   - Relationship between years of experience and salary visualized using regression plots
   - Salary grouped by experience level
   - Salary comparisons across education levels and job titles
   - Identification of highest and lowest salary job titles

## Key Insights
- Median age: **32 years**
- Mean salary: **$115,327**
- Highest-paying job: **CEO ($250,000)**
- Lowest-paying job: **Junior Business Operations Analyst ($17,675)**
- Salary trends indicate that **experience significantly impacts earning potential**

## Visualizations
The project includes multiple visualizations:
- Salary vs. Experience (Regression & Scatter plots)
- Average salary by experience group (Bar chart)
- Salary trends by education level (Bar chart)
- Most and least common job titles (Bar charts)

## Notes
- The interactive Plotly visualization **may not display properly when shared** on Kaggle.
- Salary trends show steady growth as experience increases.

## How to Use
To reproduce this analysis:
1. Run the provided Python code in the Kaggle environment.
2. Ensure necessary packages are installed.
3. Modify data visualization parameters as needed.

## Acknowledgments
This analysis is based on salary data hosted on Kaggle.
