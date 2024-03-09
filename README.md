# Weather Prediction Model 

## Introduction
This weather prediction model aims to forecast weather data using three different regression models: Ridge Regression, CatBoost Regression, and Random Forest Regression. Before running the model, it is essential to execute the Jupyter file named `Preprocessing.ipynb`, which generates `ptrain.xlsx` and `ptest.xlsx` for training and testing datasets, respectively.

## Model Performance
Based on Prediction of `mean temprature`
| Model                      | Training MSE            | Test MSE                |
| -------------------------- | ----------------------- | ----------------------- |
| Ridge Regression           | 0.0005067880976842752  | 0.0005291707799874284  |
| CatBoost Regression        | 0.02142463432953739    | 0.026728164081720216   |
| Random Forest Regression   | 0.008026658676339305   | 0.015708572702859806   |

The table above summarizes the mean squared error metrics for each regression model on both the training and test datasets. Lower MSE values indicate better model accuracy.

## Conclusion
The model provides insight into the performance of three regression models in predicting mean temperature. Careful consideration of the MSE values on both training and test datasets is crucial for selecting a model with optimal generalizability and avoiding overfitting.

It is recommended to experiment with hyperparameters and explore additional feature engineering techniques to further enhance the model's predictive capabilities.

## Instructions for Running the Model
1. Execute `Preprocessing.ipynb` to generate `ptrain.xlsx` and `ptest.xlsx`.
2. Run the weather prediction model using the provided Ridge Regression, CatBoost Regression, and Random Forest Regression models.
3. Analyze the mean squared error metrics to evaluate the performance of each model on both the training and test datasets.


