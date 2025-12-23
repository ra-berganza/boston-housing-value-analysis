# Boston Residential Property Value Analysis

## Overview
This project analyzes residential property assessment data from the City of Boston (FY2023–FY2025) to identify which property characteristics most strongly predict housing values.

Using over 400,000 property records, I built and compared multiple linear regression models to evaluate the relative importance of size, location, and physical property features.

## Key Findings
- Property size features (living area, rooms, bathrooms) explained ~37% of variation in assessed value.
- Location features (ZIP code and neighborhood) explained only ~5%, challenging the common assumption that “location is everything.”
- A combined model achieved an R² of ~0.41, with diminished accuracy for high-value properties.

## Methods
- Data cleaning and preprocessing using Pandas and NumPy
- Feature encoding and handling missing values
- Linear regression modeling with scikit-learn
- Model evaluation using train-test splits and R²
- Visualization with Matplotlib

## Files
- `DS_Final_Project.ipynb`: Full analysis and modeling workflow
- `Policy_Brief.pdf`: Written summary of findings and implications

## Data Source
City of Boston Assessing Department via data.boston.gov
