# GW-Project-4--Employee-Demographics-and-Salary-Insights-via-PowerBI

## Overview
This project provides insights into employee demographics and salary distributions using Power BI. The data is sourced from `EmployeeSampleDataCSV` and `DepartmentSampleDataCSV` files. The key metrics are displayed through various visualizations for executive review.

## Data Source
The data for this project was imported from a SQL Server database. The CSV files (`EmployeeSampleDataCSV.csv` and `DepartmentSampleDataCSV.csv`) were exported from SQL Server for use in Power BI.

## Visualizations and Insights

### 1. Ethnicity Distribution by Business Unit
**Visual: Pie Chart**

**Insight:**
- **Asian**: 432 employees, the largest group.
- **Latino**: 279 employees.
- **Caucasian**: 222 employees.
- **Black**: 67 employees.

### 2. Count of Employees by Business Unit
**Visual: Tree Map**

**Insight:**
- **Specialty Products**: 266 employees.
- **Research & Development**: 254 employees.
- **Corporate**: 254 employees.
- **Manufacturing**: 226 employees.

### 3. Average Salaries by Department
**Visual: Stacked Bar Chart**

**Insight:**
- **Human Resources**: $125.22K
- **Marketing**: $124.60K
- **Accounting**: $122.65K

### 4. Revised Salaries by Department After Bonus
**Visual: Clustered Bar Chart**

**Insight:**
- **IT**: $27.6M
- **Sales**: $17.1M
- **Engineering**: $16.7M

### 5. Count of Employees by Department Zip Code
**Visual: Stacked Column Chart**

**Insight:**
- **Zip Code 28202**: 527 employees.
- **Zip Code 90014**: 473 employees.

### 6. Count of Employees by Department
**Visual: Clustered Column Chart**

**Insight:**
- Detailed employee counts for each department.

## Live Dashboard
To view the live dashboard, click the link below:
[View Live Dashboard](https://app.powerbi.com/reportEmbed?reportId=6e442147-8121-4876-a595-f143c8be9955&autoAuth=true&ctid=845a3ea8-fd95-4405-a673-71f79900b938)

## Dashboard Image
Below is an image of the Power BI dashboard:

![Power BI Dashboard](https://github.com/ramyakrj5/GW-Project-4--Employee-Demographics-and-Salary-Insights-via-PowerBI/blob/main/GW%20Project%204-images-0.jpg)
![Power BI Dashboard](https://github.com/ramyakrj5/GW-Project-4--Employee-Demographics-and-Salary-Insights-via-PowerBI/blob/main/GW%20Project%204-images-1.jpg)
![Power BI Dashboard](https://github.com/ramyakrj5/GW-Project-4--Employee-Demographics-and-Salary-Insights-via-PowerBI/blob/main/GW%20Project%204-images-2.jpg)
![Power BI Dashboard](https://github.com/ramyakrj5/GW-Project-4--Employee-Demographics-and-Salary-Insights-via-PowerBI/blob/main/GW%20Project%204-images-3.jpg)

## How to Use
1. **Load the Data:**
   - Import the `EmployeeSampleDataCSV.csv` and `DepartmentSampleDataCSV.csv` files into Power BI.

2. **Create Measures:**
   - Define measures for key metrics such as total employees, total ethnicities, and revised salaries using DAX formulas.

3. **Build Visualizations:**
   - Use various visualizations like stacked bar charts, bar charts, column charts, clustered bar charts, map visualizations, and table visualizations to represent the data.

4. **Review Insights:**
   - Analyze the provided insights below each visual to understand the key takeaways and support decision-making.


