# csv-making
# Titanic Dataset Analysis

This repository contains code to extract and analyze data from the famous Titanic dataset. In this analysis, we focus on creating three separate datasets based on passenger classes.

## Overview

The Titanic dataset is a well-known dataset in the field of data science and machine learning. It contains various information about passengers aboard the Titanic, including their survival status, passenger class, age, and gender.

## Code Description

The main goal of the provided code is to create three separate datasets, each representing a different passenger class:

1. `pclass1.csv`: Dataset for passengers in Class 1.
2. `pclass2.csv`: Dataset for passengers in Class 2.
3. `pclass3.csv`: Dataset for passengers in Class 3.

The analysis is performed using a Python notebook. The notebook contains the following steps:

1. Reads the Titanic dataset (`train.csv`) using Pandas.
2. Selects relevant columns including `PassengerId`, `Pclass`, `Sex`, `Age`, and `Survived`.
3. Creates three dictionaries (`pclass1`, `pclass2`, and `pclass3`) to store the PassengerIds of passengers in each class.
4. Converts the dictionaries into DataFrames (`pclass1df`, `pclass2df`, and `pclass3df`) and adds the `Survived` column to each DataFrame based on the survival status of passengers in the corresponding class.
5. Calculates the probability of survival for each passenger class.
6. Inserts the `Age` column into each DataFrame with respect to the ages of passengers in that class.
7. Writes each DataFrame to a separate CSV file.

## Usage

To run the analysis:

1. Download the provided Python notebook file (`csv-making.ipynb`) and the Titanic dataset file (`train.csv`).
2. Open the notebook using Jupyter Notebook or Google Colab.
3. Execute each cell in the notebook sequentially to perform the analysis.
4. Find the generated CSV files (`pclass1.csv`, `pclass2.csv`, `pclass3.csv`) in the specified output directory.

## License

This code is licensed under the MIT License. You are free to use, modify, and distribute it as per the terms of the license.

