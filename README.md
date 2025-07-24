# Excel Project HR Employee Attrition

## Overview

Data analysis and visualization of the HR Employee Attrition data of a company on Microsoft Excel

## Business Task

To find the characteristics of employees that make them likely to exit the company

## Data Source

I obtained the dataset of a company’s HR Employee Attrition on Kaggle, and it can be found here. It contains 35 columns and 1,470 rows detailing the characteristics of the employees in the company. The analysis aims to identify key characteristics of employees that indicate a high likelihood of their leaving the company.

## Tools

Microsoft Excel

## Process

### Data Exploration and Preprocessing

* I opened the dataset on Microsoft Excel and did an initial exploration of the information it contained to understand it. I observed that some columns in the dataset needed to be standardized to accurately represent the information they contain. For example, the EnvironmentSatisfaction, JobInvolvement, JobSatisfaction, PerformanceRating, and RelationshipSatisfaction columns contained values between the numbers 1 and 5, which is not easily understood without context. I went to the source of the dataset to find the relevant information and replaced the 1 and 5 values with the proper values.

### Data Cleaning

* I deleted the EmployeeCount column because it only contained “1” as values, and that added no value to the dataset.

* After cleaning the dataset, I added a new sheet to the Excel Workbook to create pivot tables. I created a table and bar that details employee attrition by job satisfaction. Those who expressed low job satisfaction were most likely to leave the company. This likelihood was reduced the more employees there were.
