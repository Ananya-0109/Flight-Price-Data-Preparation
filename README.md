# Flight-Price-Data-Preparation
📌 Project Overview

This project focuses only on the data preparation pipeline for flight fare prediction.
It combines raw flight datasets (Business & Economy class), cleans the data, and applies feature engineering techniques to create a machine-learning-ready dataset.

The final output is a structured dataset that can be used for predictive modeling (e.g., predicting flight prices).

Link to the updated excel sheet:- https://1drv.ms/x/c/b0666c134e53ce77/ER6bxSfUuI5BjEu9j05ry7UBpN003LcSfFjwWw-cfJ7R9w?e=xhL0vg


# Steps Covered

EDA (Exploratory Data Analysis)
Checked dataset shape, dtypes, missing values
Looked at categorical vs. numerical features

Data Cleaning
Handled missing values
Converted date/time columns
Processed duration into total minutes

Feature Engineering
Extracted departure & arrival hours
Cleaned stop information

One-hot encoded categorical variables (airline, source, destination, travel class)


How to Run
# Clone repo
git clone https://github.com/<your-username>/flight-price-data-prep.git
cd flight-price-data-prep

# Install dependencies
pip install -r requirements.txt

# Run notebook
jupyter notebook notebooks/flightfare.ipynb.ipynb












