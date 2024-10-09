# DATA205- Capstone project 
The primary objective of this project is to expand the existing collection of analysis examples within the Data Science Kit. 
This project is in collaboration with the Capstone Project of the Montgomery Community College 2024 Fall intern program.



# Course Summary: DATA 205

The DATA 205 course is designed to provide students with an understanding of fundamental concepts and hands-on experience as data scientists. In addition to the more conventional learning models, this course creates a multi-professional setting where students can learn in parallel with real-life practicing professionals, thus introducing them to practical approaches to using Big Data.
One of the main traits of DATA 205 is the project-based learning approach. Students are not just consumers of these details but rather stakeholders involved in data science decisions. As students perform various tasks with real-world data, they learn how to utilize and analyze data using many methods, determine the ethical use of data, and create reproducible research results.



# Capstone Project Overview

1. Work with a mentor and data to create a “data product”
2. Special Projects
3. Opportunity to work with an external organization
4. Internal Projects
5. Defined in collaboration with the instructor



# Dataset requirements
1. Must access data from an original data source
2. Not from Kaggle or another aggregator unless the student can trace the data back to its primary source and access it there
3. Must choose and use data in a manner consistent with any licensing or usage restrictions
4. Must use real-world data (not synthetic data)
5. Must work with at least 2 quantitative (numerical) and 2 qualitative (categorical) variables
6. Must not be data the student worked with in a previous DATA course
7. There may be exceptions; instructor approval is required
8. Additional data requirements will be discussed as the student refine their project ideas



# Project Expectations

1. Choice of Topics & Datasets
2. Elevator Pitch
3. Data Ingestion, Cleaning, & Wrangling
4. Exploratory Data Analysis
5. Statistical Analysis
6. Data Visualizations
7. Data Product / Data Stories
8. GitHub Presence!


# Working with HMDA dataset
The Home Mortgage Disclosure Act of 1975 requires lenders to maintain and publicly report information about mortgage loans. This data can be beneficial in analyzing lending patterns and is instrumental in detecting discrimination.


# Key Variables for Analysis
To analyze discrimination patterns in the DMV area, I want to focus on the following variables from HMDA data:
1. Income: This can show whether or not there is discrimination by income when it comes to loaning money.
2. Sex: This can assist in revealing the gender bias in lending.
3. Race: This can be used to identify racial discrimination in the provision of mortgages.
4. Places - Geographic unit: Comparing the lending data for various areas in the DMV region - Likely census tract/ county code 
5. Age: This can go a long way in explaining whether or not age-biased mortgage lending exists.
6. Lender(Financial institution): Examining data by lender shows differences in the behaviors of different lender companies.


# Analysis of statistical method plan
1. Regression Analysis may be used to transform the number of loans approved into the variables of interest. Usually, the coefficients of each variable in a regression model indicate whether it is strongly correlated with loan approval or not.
2. Disparate Impact Analysis: This method measures the degree of variability in the rate of loan approvals between the groups. If the rate of approvals for one group is much lower than that for the other group, it can be said that disparate impact discrimination has taken place.
3. Disparate Treatment Analysis: This means going through the loan application files to look for instances of prejudice, as inspired by the law. It can be much harder to do because one has to provide actual evidence of intent on the part of the discriminating party.


# Research Questions
1. To what extent does the DMV area approve differences in mortgage loans based on income, gender, race, place, age, and agency?
2. Is the probability of being approved for a mortgage loan high or low within the DMV, and does it differ geographically?
3. Is there stratified or digressive rationality in mortgage lending in the DMV area?

