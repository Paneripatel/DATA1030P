DATA 1030 Final Project - Advertisement Click Prediction

This README provides an overview of the data preprocessing and machine learning pipeline applied to a dataset that focuses on predicting whether the user clicked the ad or not based on their demographics. This can be useful for companies to improve their marketing strategies. The pipeline addresses missing values, preprocessing data, and the application of machine learning models. 

Exploratory Data Analysis - Plotted various graphs to understand data and missing values.

Feature Selection - Removed features not relevant to the analysis.

Preprocessing Pipelines - Data Splitting, Feature Imputation, Tunning various hyperparameters.

Machine Learning Models - Several machine learning models like XGBoost, Lasso, Ridge, KNN, and ElasticNet were trained and evaluated on 5 different random states, where each model underwent hyperparameter tuning and cross-validation to optimize model performance and prevent overfitting. 

Model Evaluation - F1, Precision, and Recall scores were calculated to evaluate model performance. Calculated and plotted the importance of global and local features using metrics like SHAP, Permutation, and XGB Metrics.

Conclusions - The XGBoost model emerged as the top-performing model. The use of SHAP values offered insights into the model's decision-making processes and identified key features impacting predictions. 


Packages:
'python': "3.12.5",
'numpy': "1.26.4",
'matplotlib': "3.9.2",
'sklearn': "1.5.1",
'pandas': "2.2.2",
xgboost': "2.1.1",
'shap': "0.45.1",
'plotly': "5.23.0"


