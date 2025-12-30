# Data-Driven Insights: Oil Well Profitability and Region Selection

This project focuses on building a linear regression model to predict oil reserve volumes and identify the most profitable region for opening 200 new oil wells. Using synthetic data from three regions, the analysis combines predictive modeling, risk assessment, and profit optimization to support data-driven investment decisions.

# Objective

To test the following hypothesis:

Oil reserve volume predictions can be used to select a region that maximizes expected profit while keeping the risk of loss below 2.5%, given a fixed investment budget of $100 million.

# 🛠️ Technologies Used

Python: Pandas, NumPy, Scikit-learn

Jupyter Notebook: Interactive environment for modeling and analysis

Synthetic Datasets: Oil well data from three different regions

# Key Steps
# Data Description

Loaded and explored datasets from three regions.

Analyzed feature distributions and target variable behavior.

Verified data quality and readiness for modeling.

# Data Preprocessing and Exploration

Prepared the data for regression modeling.

Conducted exploratory data analysis to understand relationships between features and oil reserve volume.

# Model Development

Trained linear regression models for each region.

Evaluated model performance using validation techniques.

Compared prediction accuracy across regions.

# Well Selection Strategy

Predicted oil reserve volumes for all wells.

Selected the top 200 wells with the highest estimated reserves in each region.

Calculated expected profits based on predicted volumes and fixed development costs.

# Risk Analysis with Bootstrapping

Applied bootstrap simulations to estimate profit distributions.

Measured the probability of loss for each region.

Evaluated expected profit while enforcing a maximum loss risk of 2.5%.

# Results

The analysis shows that:

Linear regression models provide reliable reserve volume predictions.

Profitability varies significantly across regions.

Bootstrapping enables robust estimation of financial risk.

One region delivers the highest expected profit while maintaining an acceptable risk level below 2.5%.

Based on these findings, the project identifies the optimal region for investment and supports a confident, data-driven recommendation for opening new oil wells.
