# Goods and Trade Balance Analysis

## Description
This project provides a comprehensive data analysis of India's global trade patterns, focusing on exports for goods and services. The dataset used comes from the Ministry of Commerce and Trade, India and provides historical records that help analyze the country's trade performance over time.

The objective of this analysis is to identify trends, understand factors contributing to trade surpluses or deficits, and generate insights that can inform economic policies and business strategies. Using Exploratory Data Analysis (EDA) techniques, we have visualized the trends in trade metrics, investigated correlations, and broken down key trade indicators for better insights.

## Project Structure

- **`test.ipynb`**: The Jupyter notebook that contains the code for extracting top 5 countries based on share and growth %.
- **`netherland.ipynb`**: The Jupyter notebook that contains the code for extracting top 5 commodities based on growth % of Netherland. 
- **`france.ipynb`**: The Jupyter notebook that contains the code for extracting top 5 commodities based on growth % of France.
- **`saudiarabia.ipynb`**: The Jupyter notebook that contains the code for extracting top 5 commodities based on growth % of Saudi Arabia.
- **`uae.ipynb`**: The Jupyter notebook that contains the code for extracting top 5 commodities based on growth % of UAE.
- **`indonesia.ipynb`**: The Jupyter notebook that contains the code for extracting top 5 commodities based on growth % of Indonesia.
- **`country_wise.csv`**: The CSV file containing the country-wise dataset of export share% and growth%.
- **`netherland_commodities.csv`**: The CSV file containing Netherland's dataset of export statistics.
- **`france_commodities.csv`**: The CSV file containing France's dataset of export statistics.
- **`saudiarabia_commodities.csv`**: The CSV file containing Saudi Arabia's dataset of export statistics.
- **`uae_commodities.csv`**: The CSV file containing UAE's dataset of export statistics.
- **`indonesia_commodities.csv`**: The CSV file containing Indonesia's dataset of export statistics.
- **`README.md`**: Instructions on how to set up and run the project.
- **`requirements.txt`**: Packages required to run this project.
*all the stats are from the years 2021-2022

## Prerequisites

To run this project locally, you'll need the following installed:
- **Python 3.x**
- **Jupyter Notebook**
- **Dependencies**
- **Pandas Library**

## Analysis Overview
**1. Data Cleaning :**
Loaded the dataset using Pandas and checked for any missing, duplicate, or incorrect values.
Ensured consistency in formats (e.g., date and currency fields).
Handled any missing values by forward-filling or removing incomplete records where necessary.

**2. Exploratory Data Analysis (EDA) :**
Analyzed the dataset using statistical methods.
Correlations: Checked for correlations between key variables like Share% and Growth%
Trend Analysis: Visualized trends in exports using line plots and bar charts.
