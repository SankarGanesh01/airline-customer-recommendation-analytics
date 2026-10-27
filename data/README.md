# Dataset Documentation

## Project

**Airline Customer Recommendation Analytics**

## Dataset Overview

This project analyses an airline passenger review dataset for an academic data-mining exercise. The analysis investigates whether passenger ratings, service experience, perceived value for money, and review sentiment are associated with the recommendation outcome.

The dataset is used for coursework and is not verified real-world operational airline data. The analysis should therefore be interpreted as an illustrative application of data-mining methods, not as evidence of actual airline performance.

## Variables Used

The coursework dataset includes fields relating to:

- Airline name
- Overall rating
- Review title and review text
- Review date
- Verified review status
- Aircraft, traveller type, and seat type
- Route and date flown
- Seat comfort
- Cabin staff service
- Food and beverages
- Ground service
- Inflight entertainment
- Wi-Fi and connectivity
- Value for money
- Recommendation outcome

The target variable for classification is `Recommended`.

## Data Preparation

The accompanying analysis examines missing values and prepares selected variables for modelling. It also introduces engineered features, including `value_gap`, `service_consistency`, `experience_intensity`, and `sentiment_mismatch`, as described in the project report.

Refer to `main_analysis.ipynb` and the project report for the specific transformations and analytical workflow.

## Data Availability

The original dataset is not included in this repository. The notebook may require the original coursework dataset to be obtained separately and its input path configured before execution.

Do not upload the dataset unless you have permission to redistribute it.

## Limitations

- The dataset is not verified real-world operational airline data.
- Results should not be generalised to actual airlines without validation using appropriate real-world data.
- Missing values, feature engineering, and modelling assumptions may affect the results.
- The dataset and analysis should be used for educational and analytical demonstration only.
