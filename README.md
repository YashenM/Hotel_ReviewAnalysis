# Customer Satisfaction Analysis on Booking.com Reviews

This repository contains a statistical analysis project that explores factors influencing customer satisfaction based on a dataset of 512,470 reviews scraped from Booking.com. The objective is to identify key variables that affect reviewer scores and provide actionable insights for improving customer satisfaction.

## Project Overview

### Purpose
The goal of this project is to determine the factors that most strongly impact customer satisfaction and provide data-driven recommendations for improving customer experiences on Booking.com.

### Key Techniques
- **Data Cleaning**: Ensuring the dataset is reliable and ready for analysis.
- **Exploratory Data Analysis (EDA)**: Using techniques such as correlation matrices and scatter plots to uncover relationships between features.
- **Regression Analysis**:
  - Simple linear regression to measure individual effects.
  - Multivariate regression to combine and evaluate key variables.

### Key Findings
The strongest predictors of the `Reviewer_Score` are:
- `Average_Score`
- `Review_Total_Positive_Word_Counts`
- `Review_Total_Negative_Word_Counts`

The multivariate regression model explains 30.4% of the variance in `Reviewer_Score`, with actionable insights derived from the regression coefficients.

## Repository Structure

- `Hotel Reviews Statistical & Correlation Analyses.ipynb`: Jupyter notebook containing the detailed step-by-step statistical and correlation analyses performed on the dataset.
- `requirements.txt`: Python package dependencies required to run the analysis, including libraries like `pandas`, `numpy`, `statsmodels`, and `matplotlib`.
- `README.md`: Project overview and usage instructions.
- `customer_satisfaction_report.md`: Summary of findings and recommendations.

## How to Use
1. Clone the repository:
    ```bash
    git clone https://github.com/YashenM/Hotel_Review_Analysis.git
    ```

2. Navigate to the project directory:
    ```bash
    cd Hotel_Review_Analysis
    ```

3. Install the necessary dependencies (e.g., pandas, numpy, statsmodels, matplotlib):
    ```bash
    pip install -r requirements.txt
    ```

4. Open the Jupyter Notebook in the directory to explore the analysis:
    ```bash
    jupyter notebook
    ```

## Recommendations for Future Work
- Extend the analysis with predictive modeling using machine learning.
- Conduct residual analysis to validate regression assumptions.
- Include customer demographic data for more granular insights.
