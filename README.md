
# **Data Professional Survey Analysis**

![data.jpg](data.jpg)

# Introduction

In this project, we worked on real-world survey data related to Data Professionals from various countries.
The objective was to clean and preprocess the data before building a dashboard in Power BI to extract valuable insights about salaries, job roles, skills, and career paths in the data industry.

# Dataset Description
The dataset comes from a survey of data professionals conducted in 2023. It contains information collected from respondents working in different areas such as Data Analysis, Data Engineering, Machine Learning, and more.

Key topics covered in the dataset:

- Demographics: country, gender, education level, years of experience

- Employment details: current role, company size, remote work percentage

- Skills: tools and technologies used (e.g., SQL, Python, Power BI)

- Salaries: current and previous year's salary

- Certifications, career satisfaction, and future aspirations

Important notes:

- Some fields allowed multiple answers (e.g., tools used, certifications).

- Some fields had high frequency of "Others" responses.

- Salary data was numeric but had missing values.

# Data Cleaning Before Dashboard Creation

Before creating the dashboard, several essential data cleaning steps were performed to ensure the quality and relevance of the data:

## 1. Column Removal
We removed unnecessary columns that were either:

- Irrelevant for our analysis goals

- Containing too much noise (e.g., open-ended questions)

- Duplicating information already captured elsewhere

This helped simplify the dataset and focus only on meaningful variables.

## 2. Column Splitting
Several columns, especially those where multiple choices were possible (e.g., tools, certifications), had a large portion of responses marked as "Others".
To make the data more usable:

- We split these columns.

- We focused on the main tools/technologies used by respondents.

- "Others" responses were excluded to avoid noise and better group the main trends.

## 3. Salary Column Processing
For the column Q3: Current Year Salary:

- We had numeric salary values, but some rows had missing data.

- To handle missing salaries and outliers, we calculated the average salary for each individual (using available values).

- This helped smooth out extreme variations and ensured we had a reliable base for salary-related analyses.

# Next Steps

With the cleaned dataset, we moved on to building the dashboard in Power BI [Data_Professional_Survey_Breakdown.pptx](Data_Professional_Survey_Breakdown.pptx), focusing on key questions such as:

- Which programming langagues are the most popular among data professionals?

- What is the average salary?

- How satisfied are data professionals with their career progress?
