# DSA-Capstone-PowerBI-Project
Documentation of DSA PowerBI Project

## Table of Content

- [Project Overview](#project-overview)
- [Data Source](#data-source)
- [Tools](#tools)
- [Data Cleaning/Preparation](data-cleaning/preparation)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Data Analysis](#data-analysis)
- [Findings](#findings)
- [Recommendations](#recommendations)
- [Limitations](#limitations)

### Project Overview

This data analysis project aims to provide deep insights into gender-related issues within the organization and its regions.
To observe if there's gender equality withing the organization across board and have a critical look into salary paid to the employees through their gender classification, so
as to be able to advice the organization if there's any gap noticed.

### Data Source

There are two data set used for this analysis:
The HR employee data: "Palmoria Group emp-data(1).csv" contained detailed information about each employee of the organization

Palmoria Group Bonus Rules: "Palmoria Group Bonus Rules(1).xlsx"  contains rules for making bonus payments by the organization.

### Tools

PowerBI - For data cleaning, creating reports and visualization
-  [Download Here](https://www.microsoft.com/en-us/power-platform/products/power-bi/downloads?ocid=ORSEARCH_Bing&msockid=0739cabe1905633c0ca7de41184262b6)

### Data Cleaning/Preparation

In the initial data preparation phase, we performed the following tasks:

1. Data loading and inspection.
2. Handling missing values.
3. Data cleaning and formatting.
4. Visualization.

### Exploratory Data Analysis

EDA involved exploring the HR data to answer key questions, such as:

- Workplace Representation & Recruitment
  1. Fair and equitable hiring and advancement
  2. Gender balance across roles and levels

- Pay & Benefits Equity
  1. Equal pay and access to benefits

- Regional and Cultural Contexts : Local norms and barriers 

### Data Analysis

Include some interesting DAX (Data Analysis Expression) functions e.g
```DAX
Total Emp= COUNTROWS('Palmoria Group emp-data')
```

### Dashboard Screenshots

The screenshot are arranged according to the order of the pointers given

1. <img src="C:\Users\PC\Pictures\Screenshots\Screenshot 2025-07-05 221236.png" alt="Gender distribution">

### Findings

The analysis results are summarized as follows:

1. The organization is trying in term of gender recruitment, its glaring that the gap between the gender of employees is very small putting into consideeration that there are still some of the employees that their gender is undisclosed. Based on statistics Males are 430(49.2%), Females are 406(46.5%) and Undisclosed are 38(4.3%)

2. Across locations of the organization, headcount on gender based different is insignificant. For example in Abuja location the count of Male employess are 114(14.7%), for Female is 114(14.7%) aswell while, its just 16(5.3%) for undisclosed employees.

3. Preliminary analysis indicates a small pay gap of approximately 4% in favor of male employees, bearing in mind that employees with undisclosed gender takes 4.6% of the pay

4. With this analysis it shows that there's equality in gender across all departments. (Can be visualized on Action page)

5. The amount to be paid as bonus for each employee, the amount to be paid by locations and departments.

### Recommendations

Based on the analysis and considering the regulations adopted by the organization, we recommend the following actions:
- Employees are to have rise in pay cos just 275(31.5%) employess are earning above the minimum wage.

- The organization need to increase employees salary across regions and departments so as to be able to meet up with the regulation

### Limitations

- There are some employees that did not include their departments and some others are without salary, we had to remove them while preparing the data for analysis.
- Some of the employees did not disclose their gender, since we can't assume gender for them, we decided to categorize them as Undisclosed.
- There are some duplicates in the data provided, we had to remove the duplicate for us to arrive at a kind of conclussion very close to the actual fact







