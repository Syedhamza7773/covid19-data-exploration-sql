# Covid-19 Data Exploration using SQL

## Project Overview

This project focuses on exploring and analysing COVID-19 data using SQL Server.

The main objective of this project is to analyze Covid-19 cases, deaths, infection rates, and vaccination progress by using SQL queries and extract meaningful insights from the data.

This project demonstrates data exploration techniques used by data analysts to understand large datasets and identify important trends.

---

## Dataset Used

This project uses two datasets:

### 1. COVID-19 Deaths Dataset

This dataset contains information about COVID-19 cases and deaths.

Important columns:

- Continent
- Location
- Date
- Total Cases
- New Cases
- Total Deaths
- Population


### 2. CovidVaccinations Dataset

This dataset contains information about COVID-19 vaccination progress.

Important columns:

- Location
- Date
- New Vaccinations
- New Vaccinations Smoothed


The datasets were analysed by joining the CovidDeaths and CovidVaccinations tables based on location and date.

---

## Tools Used

- SQL Server
- SQL Server Management Studio (SSMS)
- Excel / CSV Dataset
- GitHub

---

## SQL Concepts Used

The project includes the following SQL concepts:

- SELECT statements
- Filtering using WHERE clause
- Sorting using ORDER BY
- Aggregate Functions (SUM, MAX)
- GROUP BY
- JOIN operations
- Data Type Conversion
- Window Functions
- Partition By
- Common Table Expressions (CTE)
- Temporary Tables
- Creating SQL Views

---

## Analysis Performed

The following analysis was performed:

### 1. Total Cases vs Total Deaths

Calculated death percentage to understand the likelihood of dying after contracting COVID-19.

### 2. Total Cases vs Population

Analysed what percentage of the population was infected with COVID-19.

### 3. Countries with the Highest Infection Rate

Identified countries with the highest number of Covid cases compared to their population.

### 4. Countries with the Highest Death Count

Analysed countries with the highest total deaths.

### 5. Continent Level Analysis

Compared Covid death counts across different continents.

### 6. Global COVID Numbers

Calculated overall global cases, deaths, and death percentage.

### 7. Vaccination Analysis

Analysed vaccination progress and calculated the rolling vaccinated population using window functions.

---

## Key Insights

- Identified countries with the highest infection rates compared to population size.
- Analysed countries with the highest COVID-19 death counts.
- Compared the COVID-19 impact across different continents.
- Calculated global Covid case and death statistics.
- Analysed vaccination growth over time.
- Used rolling calculations to understand vaccination progress.

---
