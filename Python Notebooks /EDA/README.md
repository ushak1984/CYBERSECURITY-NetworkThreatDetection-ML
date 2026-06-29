
# Exploratory Data Analysis

This folder contains the exploratory data analysis notebooks for the cybersecurity threat detection project.

The goal of this stage was to understand the structure, quality, and patterns in each dataset before building machine learning models.

## Datasets Analyzed

- BETH honeypot dataset
- UNSW-NB15 intrusion detection dataset
- Cybersecurity Attacks dataset

## Analysis Performed

The EDA covered:

- Dataset shape and feature review
- Missing value analysis
- Duplicate value checks
- Target variable distribution
- Univariate analysis
- Bivariate analysis
- Multivariate analysis
- Correlation heatmaps
- Class imbalance review
- Outlier and skewness review
- Feature relationship analysis

## Key Observations

- The BETH dataset showed strong behavioral patterns related to user and process activity.
- The UNSW-NB15 dataset showed important network-level patterns such as packet loss, byte counts, and connection behavior.
- The Cybersecurity Attacks dataset had quality and imbalance issues that affected modeling reliability.
- Class imbalance was an important issue to consider before interpreting model accuracy.
- Behavioral indicators were more useful than simple structural features in some parts of the analysis.

## Output

The EDA notebooks helped guide:

- Feature preprocessing decisions
- Encoding and scaling choices
- Model selection
- Evaluation strategy
- Interpretation of final model results
