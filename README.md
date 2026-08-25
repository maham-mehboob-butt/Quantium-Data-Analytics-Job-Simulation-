## Project Overview

This project documents my work completed during the Quantium Data Analytics Job Simulation on Forage.

The simulation involved analyzing transaction and customer data to identify customer purchasing patterns and evaluate the performance of trial stores using experimentation and uplift testing.

The analysis was completed using Python, with libraries including Pandas, NumPy, and SciPy.

The project covers:

- Data cleaning and preparation
- Feature engineering
- Customer segmentation
- Store-level performance analysis
- Control store selection
- Uplift testing
- Statistical significance testing
- Data-driven business insights


## Business Problem

The simulation focused on analyzing customer transaction data for a chips category and using the analysis to support data-driven business decisions.

The analysis aimed to:

- Understand customer purchasing behaviour across different customer segments.
- Identify differences in sales performance across customer life stages and premium customer groups.
- Evaluate the performance of selected trial stores against suitable control stores.
- Determine whether the trial-store results showed a statistically significant difference in sales.

The analysis was divided into two main areas: customer and transaction analysis, followed by experimentation and uplift testing.


## Task 1 — Data Preparation & Customer Segmentation

### Objective

The first task focused on preparing the transaction and customer data and analyzing purchasing behaviour across different customer segments.

### Data Preparation

The analysis involved:

- Loading the transaction and customer datasets using Pandas.
- Removing transactions with unusually high product quantities.
- Converting the transaction date into a usable datetime format.
- Removing Salsa products from the analysis.
- Extracting pack size from product names.
- Extracting and standardizing brand names.
- Merging transaction data with customer purchase behaviour data using the loyalty card number.

### Customer Segmentation Analysis

After preparing and merging the data, I analyzed:

- Total sales by customer life stage and premium customer segment.
- Number of unique customers within each segment.
- Average sales per customer.
- Average price per unit.

This allowed the customer segments to be compared based on sales performance, customer size, and purchasing value.

### Output

A cleaned and merged dataset was generated for use in subsequent analysis.


## Task 2 — Experimentation & Uplift Testing

### Objective

The second task focused on evaluating the performance of selected trial stores by comparing them with suitable control stores during the trial period.

### Store-Level Analysis

I created monthly store-level metrics including:

- Total sales
- Number of unique customers
- Transactions per customer
- Average price per unit

The data was separated into a pre-trial period and a trial period for comparison.

### Control Store Selection

For trial stores 77, 86, and 88, I developed a control-store selection method based on:

- Pearson correlation of sales
- Pearson correlation of customer numbers
- Magnitude distance for sales
- Magnitude distance for customer numbers

These measures were combined into a composite score to identify the most suitable control store for each trial store.

### Uplift Testing

During the trial period, I compared each trial store with its matched control store by:

- Calculating the percentage difference in sales.
- Performing an independent t-test.
- Evaluating the resulting p-value.
- Determining whether the sales difference was statistically significant.

A p-value below 0.05 was treated as evidence of a statistically significant sales difference.


## Tools & Technologies

- Python
- Pandas — data loading, cleaning, transformation and analysis
- NumPy — numerical calculations and statistical analysis
- SciPy — statistical hypothesis testing
- Data Analysis
- Customer Segmentation
- Experimentation & Uplift Testing
- Statistical Significance Testing


## Key Findings & Results

### Customer Analysis

The analysis produced customer-segment metrics comparing total sales, customer counts, average sales per customer, and average price per unit across different life-stage and premium-customer groups.

These metrics were used to understand differences in purchasing behaviour and customer value across segments.

### Experimentation Analysis

Trial stores 77, 86, and 88 were evaluated against matched control stores using pre-trial sales and customer metrics.

The analysis compared trial and control store performance during the February 2019 to April 2019 trial period.

Sales differences were evaluated using percentage differences and independent t-tests to determine statistical significance.

> Note: Detailed numerical findings are not included here because the available submission files contain the analysis code but not the final printed output values.


## Skills Demonstrated

- Data Cleaning & Preparation
- Data Transformation
- Feature Engineering
- Data Merging
- Customer Segmentation
- Exploratory Data Analysis
- Store-Level Performance Analysis
- Control Store Selection
- Experimentation & Uplift Testing
- Statistical Significance Testing
- Business Insight Generation
- Python for Data Analytics


## Certificate

Completed the Quantium Data Analytics Job Simulation on Forage.

Certificate of completion available as evidence of participation.
