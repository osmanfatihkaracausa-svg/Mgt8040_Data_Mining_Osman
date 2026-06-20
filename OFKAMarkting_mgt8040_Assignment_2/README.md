# OFKA Marketing Assignment 2

## Overview

This project was completed for **MGT 8040 – Data Mining & Business Analytics** at **Georgia State University** under **Dr. Lee Frank**.
The objective was to determine whether OFKA's website traffic behaves as a linear or non-linear system by comparing a Multiple Linear Regression (MLR) model with a Random Forest Regression (RF) model.

## Supporting Files

Additional project materials are available in the repository folders.

### Outputs

The Outputs folder contains:

* Final merged dataset
* Model coefficient tables
* Delta analysis results
* Top tipping-point observations
* Supporting Excel workbooks used during the analysis

### Notebook

The Notebook folder contains the Python/Jupyter Notebook used to perform:

* Data preparation
* Feature engineering
* Multiple Linear Regression modeling
* Random Forest modeling
* Delta calculations

### Data

The Data folder contains the original source datasets collected from:

* Meta Business Suite
* Google Analytics / WooCommerce

These files were used to construct the final multi-context dataset analyzed in this project.

## Dataset

The dataset combined daily website traffic metrics from Google Analytics/WooCommerce with social media metrics from Meta Business Suite, including Instagram and Facebook engagement data.

* 113 observations
* 14 predictor variables
* Target Variable: Active_Users

## Methods

* Multiple Linear Regression (MLR)
* Random Forest Regression (RF)
* Delta Analysis (Model Disagreement)

## Results

| Model                      | R² Score |
| -------------------------- | -------- |
| Multiple Linear Regression | 0.1619   |
| Random Forest Regression   | 0.8709   |

The Random Forest model substantially outperformed the linear model, indicating that OFKA's website traffic is driven by complex non-linear relationships and contextual factors.

## Key Finding

The analysis revealed hidden traffic "sweet spots" and "cliffs" where the Random Forest model detected important behavioral patterns that the linear model failed to capture.

## Technologies

* Python
* Pandas
* Scikit-Learn
* Jupyter Notebook
* Visual Studio Code

## Author

**Osman F. Karaca**
MBA Candidate – Business Analytics
J. Mack Robinson College of Business
Georgia State University