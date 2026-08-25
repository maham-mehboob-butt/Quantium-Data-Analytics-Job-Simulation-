# Quantium Data Analytics Job Simulation

> Completed through Forage

## Project Overview

This project documents my work completed during the **Quantium Data Analytics Job Simulation** on Forage.

The simulation involved analyzing transaction and customer data to identify customer purchasing patterns, evaluate trial store performance, and apply experimentation and uplift testing to support data-driven business decisions.

The analysis was completed using **Python**, with libraries including **Pandas, NumPy, and SciPy**.

The practical tasks completed as part of the simulation included:

* **Data Preparation & Customer Analysis**
* **Experimentation & Uplift Testing**
* **Analytics & Commercial Application**

The project covers:

* Data cleaning and preparation
* Feature engineering
* Customer segmentation
* Store-level performance analysis
* Control store selection
* Uplift testing
* Statistical significance testing
* Data-driven business analysis

---

## Certificate

Completed the **Quantium Data Analytics Job Simulation** through Forage.

The certificate confirms completion of the following practical tasks:

* **Data Preparation & Customer Analysis**
* **Experimentation & Uplift Testing**
* **Analytics & Commercial Application**

📜 **[View Certificate →](./Quantium_Certificate/Quantium_Data_Analytics_Job_Simulation_Certificate.pdf)**

The certificate is included as evidence of completion.


## Business Problem

The simulation focused on analyzing customer transaction data for a chips category and using the analysis to support data-driven business decisions.

The analysis aimed to:

* Understand customer purchasing behaviour across different customer segments.
* Identify differences in sales performance across customer life stages and premium customer groups.
* Evaluate the performance of selected trial stores against suitable control stores.
* Determine whether trial-store results showed a statistically significant difference in sales.

The analysis was divided into two main areas: customer and transaction analysis, followed by experimentation and uplift testing.

---

## Task 1 — Data Preparation & Customer Segmentation

### Objective

The first task focused on preparing transaction and customer data and analyzing purchasing behaviour across different customer segments.

### Data Preparation

The analysis involved:

* Loading transaction and customer datasets using Pandas.
* Removing transactions with unusually high product quantities.
* Converting transaction dates into a usable datetime format.
* Removing Salsa products from the analysis.
* Extracting pack size from product names.
* Extracting and standardizing brand names.
* Merging transaction data with customer purchase behaviour using the loyalty card number.

### Customer Segmentation Analysis

After preparing and merging the data, I analyzed:

* Total sales by customer life stage and premium customer segment.
* Number of unique customers within each segment.
* Average sales per customer.
* Average price per unit.

These metrics were used to compare customer segments based on sales performance, customer size, and purchasing value.

### Output

A cleaned and merged dataset was generated for use in subsequent analysis.

---

## Task 2 — Experimentation & Uplift Testing

### Objective

The second task focused on evaluating the performance of selected trial stores by comparing them with suitable control stores during the trial period.

### Store-Level Analysis

I created monthly store-level metrics including:

* Total sales
* Number of unique customers
* Transactions per customer
* Average price per unit

The data was separated into pre-trial and trial periods for comparison.

### Control Store Selection

For trial stores 77, 86, and 88, I developed a control-store selection method based on:

* Pearson correlation of sales
* Pearson correlation of customer numbers
* Magnitude distance for sales
* Magnitude distance for customer numbers

These measures were combined into a composite score to identify the most suitable control store for each trial store.

### Uplift Testing

During the trial period, I compared each trial store with its matched control store by:

* Calculating the percentage difference in sales.
* Performing an independent t-test.
* Evaluating the resulting p-value.
* Determining whether the sales difference was statistically significant.

A p-value below 0.05 was treated as evidence of a statistically significant sales difference.

---

## Analytics & Commercial Application

The analysis was used to translate the analytical findings into practical business insights.

Key commercial applications included:

* Identifying customer segments with higher purchasing value.
* Understanding differences in purchasing behaviour across customer groups.
* Evaluating whether trial-store performance improved during the trial period.
* Using control-store comparisons to measure the impact of the trial.
* Applying statistical testing to distinguish meaningful changes from random variation.
* Supporting data-driven recommendations for future store trials and commercial decisions.

---

## Tools & Technologies

* **Python**
* **Pandas** — data loading, cleaning, transformation, aggregation, and analysis
* **NumPy** — numerical calculations, correlations, and distance calculations
* **SciPy** — statistical hypothesis testing

### Analytical Techniques

* Data Cleaning & Preparation
* Feature Engineering
* Data Merging
* Customer Segmentation
* Exploratory Data Analysis
* Store-Level Performance Analysis
* Control Store Selection
* Experimentation & Uplift Testing
* Statistical Significance Testing

---

## Key Analysis

### Customer Analysis

The analysis produced customer-segment metrics comparing:

* Total sales
* Customer counts
* Average sales per customer
* Average price per unit

These metrics were used to understand differences in purchasing behaviour and customer value across life-stage and premium-customer groups.

### Experimentation Analysis

Trial stores 77, 86, and 88 were evaluated against matched control stores using pre-trial sales and customer metrics.

The analysis compared trial and control store performance during the February 2019 to April 2019 trial period.

Sales differences were evaluated using percentage differences and independent t-tests to assess statistical significance.

---

## Skills Demonstrated

* Data Cleaning & Preparation
* Data Transformation
* Feature Engineering
* Data Merging
* Customer Segmentation
* Exploratory Data Analysis
* Store-Level Performance Analysis
* Control Store Selection
* Experimentation & Uplift Testing
* Statistical Significance Testing
* Business Analysis
* Python for Data Analytics

---

## Project Structure

This repository provides a portfolio summary of the analysis completed during the simulation.

```text
Quantium-Data-Analytics-Job-Simulation-/
│
├── Quantium_Certificate/
│   └── Quantium_Data_Analytics_Job_Simulation_Certificate.pdf
│
└── README.md
```
Original assessment files and confidential materials are not included.

---


## Disclaimer

This repository is a personal portfolio summary of my work completed during the Quantium Data Analytics Job Simulation on Forage.

Original assessment materials, confidential documents, and proprietary content are not included in this repository.
