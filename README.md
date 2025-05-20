# Overview
A two-stage machine learning project to first predict road icing events using weather data and 
then assess how these predicted icing conditions contribute to vehicular accident risk.

**Icing Prediction Model:** Trained using weather data (temperature, precipitation, humidity, etc.) to label whether icing is likely.
**Accident Risk Model:** Uses accident records, road/weather conditions, and predicted icing risk to model accident likelihood.

# Methodology
## Stage 1: Road Icing Prediction
**Input:** Historical weather data\
**Output:** Binary label for icing occurrence\
**Model:** Random Forest\
**Evaluation:** Accuracy:- 96%, PR-AUC:- 0.98

## Stage 2: Accident Risk Prediction
**Input:** Accident dataset + predicted icing labels\
**Output:** Risk Levels (1 to 4)\
**Model:** XGBoost\
**Evaluation:** Accuracy:- 52%



