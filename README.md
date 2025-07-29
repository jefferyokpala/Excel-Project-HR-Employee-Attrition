# Excel Project HR Employee Attrition

## Overview

Data analysis and visualization of the HR Employee Attrition data of a company on Microsoft Excel. The dataset contains 35 columns and 1,470 rows detailing the characteristics of the employees in the company. The analysis aims to identify key characteristics of employees that indicate a high likelihood of their leaving the company.

## Business Task

To find the characteristics of employees that make them likely to exit the company

## Data Source

I obtained the dataset of a company’s HR Employee Attrition on Kaggle, and it can be found [here](https://www.kaggle.com/datasets/patelprashant/employee-attrition). 

## Tool

Microsoft Excel

## Process

### Data Exploration and Preprocessing

* I opened the dataset on Microsoft Excel and did an initial exploration of the information it contained to understand it. I observed that some columns in the dataset needed to be standardized to accurately represent the information they contain. For example, the EnvironmentSatisfaction, JobInvolvement, JobSatisfaction, PerformanceRating, and RelationshipSatisfaction columns contained values between the numbers 1 and 5, which is not easily understood without context. I went to the source of the dataset to find the relevant information and replaced the 1 and 5 values with the proper values.

### Data Cleaning

* I deleted the EmployeeCount column because it only contained “1” as values, and that added no value to the dataset.

* After cleaning the dataset, I added a new sheet to the Excel Workbook to create pivot tables. I created a table and bar chart that details employee attrition by job satisfaction. Those who expressed low job satisfaction were most likely to leave the company. This likelihood was reduced the more employees there were.

![image alt](https://github.com/jefferyokpala/Excel-Project-HR-Employee-Attrition/blob/main/images/image6.png?raw=true)

![image alt](https://github.com/jefferyokpala/Excel-Project-HR-Employee-Attrition/blob/main/images/image7.png?raw=true)

* Next, I created a pivot chart and a horizontal clustered bar chart to visualize the employee attrition by overtime data. From the visual, I could easily see that attrition was more common amongst employees who worked overtime. 30% of employees who worked overtime exited the company, which is significantly higher than the 10% attrition rate of those who did not. This led me to conclude that working overtime is a significant factor that contributes to employee attrition in the company.

![image alt](https://github.com/jefferyokpala/Excel-Project-HR-Employee-Attrition/blob/main/images/image9.png?raw=true)

![image alt](https://github.com/jefferyokpala/Excel-Project-HR-Employee-Attrition/blob/main/images/image4.png?raw=true)

* Afterwards, I wanted to find out if there is a department more prone to attrition than others. Therefore, I created a pivot table and a combination chart of bars and lines. I observed that the attrition rate was similar across the three departments, ranging from 13%-20%, with the sales department having the highest rate and R&D having the lowest.  I noted this trend but did not feel confident enough to draw a solid conclusion from it.

![image alt](https://github.com/jefferyokpala/Excel-Project-HR-Employee-Attrition/blob/main/images/image3.png?raw=true)

![image alt](https://github.com/jefferyokpala/Excel-Project-HR-Employee-Attrition/blob/main/images/image2.png?raw=true)

* Given my reluctance to draw solid conclusions from the attrition patterns by department, I decided to analyze the attrition rate by job level and created a pivot table and line chart to visualize that data. I observed that attrition is most common amongst people who are at level 1 and relatively low in other levels. This may be due to entry-level employees leaving to start their careers at other companies they believe are better for their career development. However, the attrition rate for employees in level 3 ticked up a bit, suggesting that people in the category may be looking for substantial pay raises by leaving for another company.

![image alt](https://github.com/jefferyokpala/Excel-Project-HR-Employee-Attrition/blob/main/images/image8.png?raw=true)

![image alt](https://github.com/jefferyokpala/Excel-Project-HR-Employee-Attrition/blob/main/images/image5.png?raw=true)

* To conclude, I created a dashboard showcasing my findings for easy presentation to business stakeholders. I added slicers to the dashboard to filter the charts on the dashboard by gender, business travel frequency, marital status, and work-life balance to drill further into the data for each characteristic and extract more insight.

![image alt](https://github.com/jefferyokpala/Excel-Project-HR-Employee-Attrition/blob/main/images/image1.png?raw=true)
