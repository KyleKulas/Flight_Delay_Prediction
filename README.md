# Lighthouse Labs Mid-Term Project

## Flights Delay Prediction
By Kyle, Yusri and Arash

This project analysed commercial flight data in the US in 2018 and 2019. The data was accessed through Lighthouse labs server Postgress server and contains approximate 15M flight records. This data was used to train various models to predict flight delays. External weather data was used to increase model performance. 

### Model performance
| Model | RMSE|
|---|---|
| XGBoost | 32.6 | 
| Random Forest Regression | 49.1 |
| Linear Regression | 51.7 |
| Naive Bayes | 144.1 |


Final submission is our best predictions for Jan 2020 flight data using the XGBoost model.