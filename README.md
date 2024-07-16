# BCGX GENAI SIMULATION

## Overview

The BCGX GENAI SIMULATION is a prototype Python application designed to simulate a financial chatbot using natural language processing (NLP). It interprets predefined financial queries to retrieve and present data from a CSV file (`Book.csv`) containing financial metrics for companies like Microsoft, Tesla, and Apple across multiple years.

This simulation serves as an introductory project for understanding basic chatbot development principles, NLP techniques, and data retrieval functionalities.

## Features

- **Predefined Queries**: Supports queries related to financial metrics available in the `book.csv` dataset.
  
- **Natural Language Processing (NLP)**: Utilizes NLTK for tokenization and stopwords removal to interpret user queries.
  
- **Data Retrieval**: Retrieves the latest financial data from `book.csv` based on user queries.
  
- **Error Handling**: Provides basic error handling for unmatched queries or data retrieval issues.

## Files Included

- **`chatbot.ipynb`**: Main Python script containing the chatbot logic.
  
- **`Book.csv`**: Sample CSV file containing financial data for companies (Microsoft, Tesla, Apple) across multiple years.

- **`BCGX.ipynb`**: Python script for data preprocessing and analysis.
  
## Data Analysis

The `BCGX.ipynb` script preprocesses and analyzes the financial data in `book.csv`:

- **Data Cleaning**: Converts columns containing numeric data from string format to numeric format.
  
- **Calculates Growth**: Computes year-over-year percentage changes in revenue and net income for each company.
  
- **Average Growth**: Computes average revenue and net income growth across the years available in the dataset.
