# Apartment Rental Data Analysis

This project explores apartment rental data through preprocessing, feature engineering, sampling methods, and exploratory data analysis. The notebook focuses on preparing the dataset, comparing sampling strategies, and identifying patterns in rental prices across locations and property features.

## Project Overview

The goal of this project is to clean and prepare apartment rental data, examine important variables, and visualize relationships that may influence rental pricing. The notebook includes data cleaning, handling missing values, outlier treatment, sampling comparison, and several EDA visualizations.

## Dataset

A similar publicly available dataset can be found here:

<a href= "https://www.kaggle.com/datasets/shashanks1202/apartment-rent-data/data"> Kaggle dataset link </a>

If you use the dataset from the link above, the file may not be identical to the one used in the notebook, but it is still suitable for similar preprocessing and exploratory analysis.

## Main Steps

- Data loading and inspection.
- Duplicate removal.
- Missing value handling.
- Timestamp conversion and feature extraction.
- Outlier removal using the IQR method.
- Simple random, systematic, and stratified sampling.
- Exploratory data analysis and visualization.
- Feature engineering, including price per square foot.

## Key Insights

- Rental price varies by location, property size, and amenities.
- Stratified sampling preserves city representation more effectively than the other sampling methods in this notebook.
- Price per square foot provides a useful way to compare properties across locations.
- Several visualizations suggest that location and amenities contribute to rental pricing patterns.

## Files

- `19_P1.ipynb` — Main notebook containing preprocessing and analysis.
- `README.md` — Project description and usage information.

## Future Work

Future work could include building a predictive model for rental price using the cleaned dataset and exploring feature importance across different property and location variables.

## Notes

This repository is intended as a data preprocessing and exploratory analysis project.
