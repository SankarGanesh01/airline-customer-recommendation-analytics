# Project Documentation

## 1. Project Overview

**Airline Customer Recommendation Analytics** is an academic data-mining project examining airline passenger recommendation behaviour using structured service ratings and written-review sentiment.

The project combines exploratory data analysis, feature engineering, classification modelling, sentiment analysis, and visualisation.

## 2. Research Objectives

The project aims to:

- Explore passenger ratings and recommendation outcomes.
- Examine relationships between service quality and perceived value for money.
- Engineer features that represent aspects of passenger experience.
- Compare Logistic Regression and Random Forest classification approaches.
- Apply TextBlob and VADER to analyse review sentiment.
- Explore the contribution of sentiment-related features to recommendation prediction.

## 3. Repository Contents

| File or folder | Purpose |
|---|---|
| `main_analysis.ipynb` | Interactive Python analysis |
| `report/` | Academic project report |
| `figures/` | Selected analytical charts |
| `data/` | Dataset documentation, if retained |
| `requirements.txt` | Python package dependencies |
| `README.md` | Project overview and methodology |
| `.gitignore` | Excludes local data and temporary files |

## 4. Analytical Methods

The report and notebook cover descriptive analysis, feature engineering, classification modelling, and sentiment analysis.

The classification approaches include Logistic Regression and Random Forest. TextBlob and VADER are used to derive sentiment information from written reviews.

The visualisations explore feature correlations, model feature importance, recommendation probabilities, and the relationship between Value for Money ratings and recommendation outcomes.

## 5. Dataset Disclaimer

The dataset used in this coursework is not verified real-world operational airline data. Consequently, the project does not establish actual airline service quality, passenger satisfaction levels, or real-world airline performance.

Its purpose is to demonstrate the application of data-mining techniques to a passenger recommendation problem.

## 6. Reproducibility

The repository includes the analysis notebook, report, and selected visualisations, but does not include the original dataset.

To execute the notebook, users must obtain the required dataset separately, configure the relevant input path, and install the dependencies listed in `requirements.txt`.

Results may differ if the dataset, package versions, preprocessing steps, or model settings differ from those used in the original analysis.

## 7. Interpretation and Limitations

- Correlation does not establish causation.
- Feature importance describes a model's predictive behaviour, not necessarily causal influence.
- Model predictions should not be interpreted as guarantees.
- Evaluation results are specific to the dataset and methodology used.
- Real-world application would require validation on suitable, authentic airline review data.

## 8. Main Report

The full report is available at:

[`report/Airline_Customer_Recommendation_Analytics_Report.pdf`](../report/Airline_Customer_Recommendation_Analytics_Report.pdf)
