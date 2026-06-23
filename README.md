# SQL Layoffs Data Analysis Project

## Project Overview

This project analyzes a global layoffs dataset using MySQL. The objective was to clean raw data and perform exploratory data analysis (EDA) to uncover trends in layoffs across companies, industries, countries, and funding stages.

## Dataset

Global Layoffs Dataset

## Tools Used

* MySQL
* GitHub

## Data Cleaning Tasks

* Removed duplicate records using ROW_NUMBER()
* Standardized company, industry, and country names
* Converted text dates into DATE format
* Handled NULL and blank values
* Removed incomplete records

## Exploratory Data Analysis

### Business Questions Answered

1. Which companies had the highest number of layoffs?
2. Which countries experienced the most layoffs?
3. How did layoffs change over time?
4. Which funding stages were most affected?
5. Which companies laid off 100% of employees?
6. What were the monthly layoff trends?
7. What is the cumulative (rolling) layoffs trend over time?
8. Which companies ranked among the top layoffs each year?

## SQL Concepts Demonstrated

* CTEs
* Window Functions
* DENSE_RANK()
* ROW_NUMBER()
* Aggregate Functions
* GROUP BY
* Date Functions
* Rolling Totals
* Data Cleaning Techniques

## Key Insights

* Certain technology companies recorded the highest layoffs.
* Layoffs peaked during specific economic downturn periods.
* The United States accounted for the largest number of layoffs.
* Several startups conducted complete workforce reductions despite significant funding.

## Project Files

* layoffs_data_cleaning.sql
* layoffs_eda.sql

## Author

Shivam Neeraj
Aspiring Data Analyst
