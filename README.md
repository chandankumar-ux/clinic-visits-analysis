# Clinic Visits Analysis

An end-to-end data analysis project exploring clinic visit data to uncover patterns in patient demographics, departments, waiting times, consultation duration, fees, and follow-up behavior.

## Overview

Healthcare organizations generate large amounts of operational data during patient visits. This project uses Python and data analysis techniques to explore that data and identify useful patterns related to patient visits and clinic operations.

The analysis covers data cleaning, exploratory data analysis, statistical analysis, probability, sampling, and visualization.

## Objectives

- Clean and prepare clinic visit data for analysis
- Explore patient and visit characteristics
- Analyze waiting and consultation times
- Compare departments and cities
- Analyze consultation fees and identify potential outliers
- Investigate follow-up visit patterns
- Apply probability concepts to real-world data
- Explore sampling distributions and the Central Limit Theorem
- Communicate findings through clear visualizations

## Dataset

The dataset contains clinic visit records with information such as:

- Patient and visit identifiers
- Visit dates
- Medical departments
- Doctors
- Patient age and gender
- City
- Waiting time
- Consultation duration
- Consultation fees
- Payment method
- Follow-up status
- Procedure information

## Analysis

### Data Cleaning

The data preparation process includes:

- Handling missing values
- Standardizing categorical values
- Validating dates
- Checking data types
- Identifying duplicate records
- Detecting unusual or invalid values
- Identifying potential fee outliers

### Exploratory Data Analysis

The analysis investigates:

- Patient age distribution
- Department-level visit patterns
- City-level differences
- Waiting time distribution
- Consultation duration
- Consultation fee patterns
- Payment methods
- Follow-up behavior

### Statistical Analysis

The project also explores:

- Descriptive statistics
- Probability of specific patient/visit events
- Relationships between numerical variables
- Sampling distributions
- Central Limit Theorem
- Outlier detection using the IQR method

## Visualizations

The project uses visualizations to understand patterns and relationships in the data, including:

- Histograms
- Box plots
- Bar charts
- 2D histograms
- Correlation heatmaps

## Tech Stack

- **Python**
- **Pandas** – data manipulation and analysis
- **NumPy** – numerical computing
- **Matplotlib** – data visualization
- **Seaborn** – statistical visualization
- **Jupyter Notebook** – analysis environment

## Project Structure

```text
clinic-visits-analysis/
│
├── starter/
│   ├── README.md
│   └── clinic_visits_2025.csv
│
└── README.md
