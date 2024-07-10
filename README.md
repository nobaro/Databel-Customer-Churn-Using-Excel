# Databel Customer Churn Using Excel
![]()

## Introduction
This Excel project focuses on Customer Churn Analysis for a telecom company named Databel. In this project, I will analyze the factors contributing to customer churn and provide insights to help Databel understand and reduce churn rates. This will ultimately enhance customer retention and grow its customer base.

## Problem Statement
1. What are the primary factors driving customer churn at Databel?
2. What patterns and trends can be identified from the customer data to pinpoint the reasons for churn?
3. How do customer demographics and usage behaviors correlate with customer churn rates?
4. How can these insights be translated into actionable strategies to reduce customer churn and improve retention?

## Skills Demonstrated
The following Excel features were incorporated:
- Logical Functions
- Conditional Formulas
- Pivot Tables
- Filters
- Exploratory Data Analysis

## Data Sourcing
The dataset for this analysis was sourced from a DataCamp case study - [Analyzing Customer Churn in Excel](https://medium.com/r/?url=https%3A%2F%2Fapp.datacamp.com%2Flearn%2Fcourses%2Fcase-study-analyzing-customer-churn-in-excel) and the link to the dataset can be found [here](https://medium.com/r/?url=https%3A%2F%2Fs3.amazonaws.com%2Fassets.datacamp.com%2Fproduction%2Frepositories%2F6386%2Fdatasets%2FDatasets%2Band%2BWorkbooks.zip).

The dataset contains 29 columns and 6,688 rows, each representing a unique customer.

## Data Preprocessing
I conducted a thorough evaluation of the dataset to identify any potential data quality issues that might require cleaning. 

Some of the applied steps include:
- Converting the data range into a table for easier manipulation and analysis
- Utilizing Excel's "Remove Duplicates" feature to ensure the dataset was free of repeated entries
- Creating a new column "churned" to the customer's table that assigns numeric values to the return response of YES and NO. If YES, then 1, else 0. `=IF([@[Churn Label]]="Yes", 1, 0)`

It's worth noting that no issues were found within the dataset.

## Data Analysis
### Exploratory Data Analysis 
This aim is to summarize essential data characteristics using visual methods and summary statistics. This plays a pivotal role for Databel by identifying complex patterns in churn rates, pinpointing anomalies, and validating assumptions through comprehensive analysis and graphical representations.

The steps include:
- Calculating churn
- Investigating churn
- Digging Deeper into Churn Categories

### Advanced Data Analysis
A more thorough analysis which included taking a holistic approach to uncover deeper, more detailed insights.

The steps include:
- Analyzing demographics
- Analyzing age groups
- Analyzing call plans
- Analyzing international call behaviors 

The Data analysis was well detailed in my article [here]()

## Data Visualization
