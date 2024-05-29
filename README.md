# Credit Limit Prediction using Regression
Predicting credit limits is crucial for financial institutions to assess risk and make informed lending decisions. This project focuses on using regression models to predict credit limits based on various customer attributes.

## Preprocessing Data
Before training our model, we preprocess the data to ensure its quality and suitability for analysis. This includes removing irrelevant columns, handling duplicate data, encoding categorical features, and splitting the data into training and testing sets.

## Handling Missing Data
Missing data is a common issue in datasets and can significantly impact model performance. We employ strategies such as imputation based on mean or median values and leveraging relationships between features to fill missing data appropriately.

## Handling Outliers
Outliers can skew model predictions and affect the overall accuracy. We identify and remove outliers using techniques like Local Outlier Factor (LOF) to ensure robust model training.

## Feature Selection
Selecting the most relevant features is crucial for model efficiency and interpretability. We use techniques like correlation analysis and feature importance scores to select the most informative features for our regression model.

## Model Training
We train regression models, such as RandomForestRegressor, on the preprocessed data to predict credit limits. We fine-tune model parameters and evaluate performance to ensure optimal results.

## Evaluation
We evaluate model performance using metrics such as Mean Squared Error (MSE) and R-squared. Additionally, we assess model stability through cross-validation and compare results across multiple runs.

## Conclusion
In conclusion, this project demonstrates the application of regression models for credit limit prediction. By preprocessing data, handling missing values and outliers, and selecting informative features, we build robust models that can assist financial institutions in making informed lending decisions.

## Contributing
Contributions to this project are welcome! If you have any suggestions, improvements, or bug fixes, feel free to open an issue or submit a pull request.
