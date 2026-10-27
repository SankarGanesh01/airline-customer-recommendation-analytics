# Project Visualisations

This directory contains five visualisations from the Airline Customer Recommendation Analytics project.

## 1. Correlation Heatmap

**File:** `correlation-heatmap.png`

Explores pairwise correlations among selected service ratings, recommendation outcomes, and engineered features. Blank areas may indicate unavailable or undefined correlations, so they should not be interpreted as zero correlation.

## 2. Feature Importance

**File:** `feature-importance.png`

Displays feature importance scores for the model represented in the report's chart. Value for Money has the largest displayed importance, followed by Cabin Staff Service and sentiment.

Importance scores describe the fitted model's relative feature contributions; they do not demonstrate causation. The exact model and importance calculation should be identified in the accompanying report or code if available.

## 3. Recommendation Probability Heatmap

**File:** `recommendation-probability-heatmap.png`

Displays estimated recommendation probabilities for combinations of Cabin Staff Service and Value for Money ratings. The estimates shown generally rise as the two ratings increase.

These are model-based estimates for the analysed dataset, not guaranteed outcomes or validated probabilities for real airline passengers.

## 4. Value for Money vs Recommendation

**File:** `value-for-money-vs-recommendation.png`

Compares Value for Money rating distributions between recommendation classes: `0` and `1`. The chart illustrates the relationship between perceived value and the recommendation label in the dataset.

## 5. Value vs Overall Rating vs Recommendation

**File:** `value-vs-rating-vs-recommendation.png`

Plots Overall Rating against Value for Money, using colour to distinguish the recommendation classes.

## Data Disclaimer

The figures are based on the coursework dataset, which is not real-world operational airline data. They are included to illustrate the project's analytical approach and should not be treated as verified evidence of actual airline performance.
