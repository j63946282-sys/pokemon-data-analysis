# Pokemon Data Analysis Project

## Overview

This project focuses on cleaning, preparing, and analyzing a Pokemon dataset using Python and Pandas.
It demonstrates essential data skills useful for data analyst and data science internships.

## Project Goals

* Clean and prepare raw data
* Handle missing values
* Remove duplicates
* Engineer new features
* Perform exploratory data analysis (EDA)
* Export cleaned data and summary tables

## Dataset

The dataset used in this project contains information about:

* Pokemon Name
* Types (Type 1, Type 2)
* Stats (HP, Attack, Defense, Special Attack, Special Defense, Speed)
* Generation
* Legendary status

## Steps Performed

### 1. Load Data

Loaded the CSV file into a Pandas DataFrame.

### 2. Explore Data

* Viewed first rows
* Checked data types
* Summarized numerical columns
* Counted missing values

### 3. Clean Data

* Filled missing Type 2 values with "None"
* Removed all duplicate rows
* Confirmed cleaning by re-checking missing values and duplicates

### 4. Feature Engineering

Created new columns:

* **Total**: Sum of all stat values
* **Is_Fast**: Boolean column based on Speed > 100

### 5. Exploratory Analysis

Performed basic analysis such as:

* Pokemon type distribution
* Fast vs non-fast Pokemon
* Average total stats per generation
* Sorting by strongest Pokemon

### 6. Export Results

Exported the cleaned dataset and grouped summary:

* `cleaned_pokemon.csv`
* `avg_stats_by_type.csv`

## Technologies Used

* Python
* Pandas
* NumPy
* Jupyter Notebook

## Files in This Repository

* `pokemon_analysis.ipynb` — full notebook with code and analysis
* `pokemon_data.csv` — original dataset
* `cleaned_pokemon.csv` — cleaned dataset
* `avg_stats_by_type.csv` — summary statistics by type

## Conclusion

This project demonstrates practical experience in:

* Data cleaning
* Data manipulation
* Feature engineering
* Data analysis with Pandas
* Preparing datasets for further analysis

This project is part of my portfolio for data-related internships.
