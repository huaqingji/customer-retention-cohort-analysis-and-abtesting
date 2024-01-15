# Customer Retention Cohort Analysis and A/B Testing


1. Introduction
- This project is based on the transaction data for a retail store. The source data, which is from Kaggle, contains three datasets: transaction, customer, and product hierarchy. The project aims to perform exploratory data analysis, cohort analysis, and A/B testing on the source data, with the customer retention as the KPI metric in particular.  Various data cleaning, transformation, integration, wrangling, aggregation, and visualization are also implemented.


2. Implementation
- Performed exploratory data analysis (EDA), data cleaning, data integration, and data wrangling on retail data
- Defined customer retention as KPI metric and conducted cohort analysis with corresponding heatmap visualization
- Implemented A/B testing experiment (hypothesis testing) on retention rate with parametric and simulation methods


3. Table of Contents
- **[1. Import Data](#1)**
    - [1.1. Import Customer Data](#1.1)
    - [1.2. Import Product Hierarchy Data](#1.2)
    - [1.3. Import Transaction Data](#1.3)
- **[2. Data Cleaning and Transformation](#2)**
    - [2.1. Data Cleaning for Customer Data](#2.1)
        - [2.1.1. Check and Remove Missing Values](#2.1.1)
        - [2.1.2. Check and Remove Duplicated Records](#2.1.2)
        - [2.1.3. Convert Data Types](#2.1.3)
    - [2.2. Data Cleaning for Product Hierarchy Data](#2.2)
        - [2.2.1. Check and Remove Missing Values](#2.2.1)
        - [2.2.2. Check and Remove Duplicated Records](#2.2.2)
    - [2.3. Data Cleaning for Transaction Data](#2.3)
        - [2.3.1. Check and Remove Missing Values](#2.3.1)
        - [2.3.2. Check and Remove Duplicated Records](#2.3.2)
        - [2.3.3. Check and Remove Transactions with Nonpositive Quantity](#2.3.3)
        - [2.3.4. Convert Data Types](#2.3.4)
- **[3. Data Integration](#3)**
- **[4. Exploratory Data Analysis (EDA)](#4)**
    - [4.1. Explore Numerical Data](#4.1)
        - [4.1.1. Data Location and Variability](#4.1.1)
        - [4.1.2. Data Distribution](#4.1.2)
    - [4.2. Explore Categorical Data](#4.2)
        - [4.2.1. Pie Plot for Categories](#4.2.1)
        - [4.2.2. Bar Plot for Categories](#4.2.2)
    - [4.3. Explore Multiple Variables and Facet Grids](#4.3)
- **[5. Customer Retention Cohort Analysis](#5)**
    - [5.1. Define the Time Interval for Retention](#5.1)
    - [5.2. Data Wrangling and Aggregation for Cohort Matrix](#5.2)
    - [5.3. Cohort Analysis and Heatmap Visualization](#5.3)
    - [5.4. Conclusion](#5.4)
- **[6. Customer Retention A/B Testing](#6)**
    - [6.1. Data Preparation and Analysis](#6.1)
        - [6.1.1. Filter Data](#6.1.1)
        - [6.1.2. Calculate KPI Metric](#6.1.2)
        - [6.1.3. Retrospective Analysis](#6.1.3)
    - [6.2. A/B Testing](#6.2)
        - [6.2.1. Define Experiment Group and Control Group](#6.2.1)
        - [6.2.2. Hypothesis Testing - Parametric Method - Self Defined Z Test](#6.2.2)
        - [6.2.3. Hypothesis Testing - Parametric Method - Statistical Library Z Test](#6.2.3)
        - [6.2.4. Hypothesis Testing - Simulation Method](#6.2.4)
    - [6.3. Conclusion](#6.3)


4. Reference
- https://www.kaggle.com/darpan25bajaj/retail-case-study-data
