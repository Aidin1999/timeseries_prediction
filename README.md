# Predicting Coronavirus Vaccinations

## Project Overview

This project focuses on predicting the number of coronavirus vaccinations administered over time. It was undertaken as part of a series of projects for obtaining a Machine Learning certification. The primary goal was to develop a model capable of forecasting vaccination trends based on historical data.

## Objective

The main objectives of this project were to:
- **Forecast Future Vaccination Counts**: Utilize historical vaccination data to predict the number of vaccinations that will be administered in the future.
- **Evaluate Model Performance**: Assess the performance of different machine learning models to determine which provides the most accurate predictions.
- **Select and Fine-Tune the Best Model**: Identify and optimize the best-performing model to ensure accurate forecasting.

## Data

The dataset used in this project includes:
- **Date**: The specific date when the vaccination data was recorded.
- **Total Vaccinations**: The cumulative number of vaccinations administered up to that date.

> **Note:** Due to security and privacy concerns, the specific dataset used in this project cannot be shared. However, the general methodology and approach are described here.

## Methodology

### Data Preparation
1. **Data Aggregation**: The daily vaccination counts were aggregated to calculate the total number of vaccinations per date.
2. **Data Cleaning**: Missing values were handled, and data consistency was ensured.

### Feature Engineering
- **Date Conversion**: Dates were converted into a format suitable for modeling.
- **Scaling**: The total vaccination counts were normalized to improve model performance.

### Model Selection and Training
1. **Model Initialization**: An XGBoost Regressor model was initialized with selected hyperparameters.
2. **Hyperparameter Tuning**: GridSearchCV was used to find the optimal parameters for the model.
3. **Model Training**: The model was trained using the training data.

### Model Evaluation
- The performance of the model was evaluated using metrics such as R² score, Mean Squared Error (MSE), and Mean Absolute Error (MAE).
- Different parameter settings and models were compared to determine the best performer.

## Conclusion

The project successfully demonstrated the application of machine learning techniques to predict vaccination trends. The final model was evaluated and saved, making it available for future use and accurate forecasting.

> **Note:** Due to security and privacy concerns, the specific dataset used in this project cannot be shared. The code and methodology provided illustrate the approach taken and the techniques applied during the project.

## References

- [XGBoost Documentation](https://xgboost.readthedocs.io/)
- [Scikit-Learn Documentation](https://scikit-learn.org/stable/documentation.html)
- [Joblib Documentation](https://joblib.readthedocs.io/en/latest/)
