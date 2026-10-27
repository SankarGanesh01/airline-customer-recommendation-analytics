# Airline Customer Recommendation Analytics

**Data Mining | Machine Learning | Customer Review Analytics | Sentiment Analysis**

## Project Overview

This project investigates airline passenger recommendation behaviour using descriptive analytics, feature engineering, classification models, and sentiment analysis of written reviews.

The study examines how passenger service ratings, perceived value for money, overall ratings, and review sentiment relate to the binary recommendation outcome. It compares Logistic Regression and Random Forest approaches and explores whether sentiment-derived features add information to structured rating data.

**Dataset disclaimer:** The dataset used in this coursework is not real-world operational airline data. The results are presented as an analytical exercise and should not be interpreted as verified evidence of actual airline performance.

## Project Objectives

- Explore passenger ratings and recommendation outcomes.
- Examine relationships between service quality, perceived value, and recommendation behaviour.
- Engineer features representing value differences, service consistency, and passenger experience.
- Compare Logistic Regression and Random Forest classification approaches.
- Apply TextBlob and VADER for review sentiment analysis.
- Explore the predictive contribution of sentiment and service-related features.
- Communicate findings through visualisations and a written analytical report.

## Methodology

### 1. Data Preparation and Exploration

The report examines the dataset's structure, rating variables, recommendation labels, and missing values before modelling.

### 2. Feature Engineering

The analysis includes engineered variables such as:

- `value_gap`
- `service_consistency`
- `experience_intensity`
- `sentiment_mismatch`

These features are intended to capture aspects of the passenger experience beyond individual ratings.

### 3. Predictive Modelling

The report compares two classification approaches:

- Logistic Regression
- Random Forest

The target variable is the binary recommendation outcome, `Recommended`.

### 4. Sentiment Analysis

The project uses TextBlob and VADER to derive sentiment information from written passenger reviews. It also examines combined sentiment information alongside structured numerical features.

### 5. Evaluation

The report describes a time-based training and testing approach. Its reported results should be interpreted in the context of the dataset, feature engineering, and evaluation design; they are not proof of performance on real-world airline data.

## Selected Visualisations

### Correlation Heatmap

Explores relationships between selected ratings, recommendation outcomes, sentiment, and engineered features.

![Correlation Heatmap](figures/correlation-heatmap.png)

### Feature Importance

Shows the relative importance scores displayed for selected features in the fitted model.

![Feature Importance](figures/feature-importance.png)

### Recommendation Probability Heatmap

Displays estimated recommendation probabilities across combinations of Cabin Staff Service and Value for Money ratings.

![Recommendation Probability Heatmap](figures/recommendation-probability-heatmap.png)

### Value for Money vs Recommendation

Compares Value for Money ratings between the two recommendation classes.

![Value for Money vs Recommendation](figures/value-for-money-vs-recommendation.png)

### Value vs Overall Rating vs Recommendation

Shows the relationship between Value for Money, Overall Rating, and the recommendation class.

![Value vs Rating vs Recommendation](figures/value-vs-rating-vs-recommendation.png)

For descriptions and interpretation notes, see [`figures/README.md`](figures/README.md).

## Tools and Techniques

The report describes the use of:

- **Language:** Python
- **Data handling:** Pandas, NumPy
- **Machine learning:** Scikit-learn
- **Sentiment analysis:** TextBlob, VADER
- **Methods:** Exploratory data analysis, feature engineering, classification, sentiment analysis, and model evaluation

These tools are listed to document the methodology described in the report. The repository does not currently include the executable code or environment specification.

## Repository Contents

| Path | Description |
|---|---|
| `report/` | Full project report |
| `figures/` | Five selected analytical visualisations and their documentation |
| `docs/` | Project documentation and data limitations |
| `README.md` | Project overview, methods, and visualisations |
| `.gitignore` | Excludes common temporary and local development files |

## Limitations

- The coursework dataset is not real-world operational airline data.
- The results are illustrative and should not be generalised to actual airlines.
- Predictive associations do not establish causal relationships.
- Model results depend on data quality, feature construction, and the evaluation method.
- The repository contains the report and selected figures, not the source dataset, notebooks, or executable scripts.
- Independent reproduction of the reported results is not possible from the current repository alone.

## Project Report

Read the complete report: [`Airline_Customer_Recommendation_Analytics_Report.pdf`](report/Airline_Customer_Recommendation_Analytics_Report.pdf).


