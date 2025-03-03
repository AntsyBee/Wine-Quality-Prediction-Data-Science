# Wine Quality Analysis using Data Modeling Techniques

## Overview

This project investigates the dependence of wine quality on multiple variables using various data modeling techniques. The dataset contains attributes such as sugar content, alcohol percentage, and pH, which are analyzed through regression, k-NN, and k-means clustering models.

## Data Preparation

- Cleaned the dataset by removing null values, whitespace, and non-numeric entries.
- Addressed outliers using the Interquartile Range (IQR) method with a threshold of 1.5.
- Randomly sampled 600 values, stored as `A2RandomSample.csv`, used throughout the analysis.

## Technologies Used

- Python
- Pandas
- Scikit-learn
- Matplotlib
- Seaborn

## References

- [Scikit-learn Documentation](https://scikit-learn.org/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- RMIT Course Modules on Practical Data Science

## Author

**Monty Sefer**  
School of Science, RMIT University  
October 2023

---

This repository contains:
- The dataset (`A2RandomSample.csv`).
- Code implementations for data processing, regression, k-NN, and k-means clustering.
- Visualizations generated for model evaluation.