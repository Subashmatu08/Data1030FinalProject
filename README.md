# Data1030FinalProject

This README provides an overview of the data preprocessing and machine learning pipeline applied to a healthcare dataset focused on thyroid-related health data. The pipeline addresses missing values, data transformation, and the application of machine learning models to predict health outcomes.

## Data Preprocessing

The preprocessing steps are crucial for preparing the dataset for machine learning algorithms. These steps include:

    - Missing Value Analysis: Findout the fraction of missing values in the data set

    - Feature Selection: Removal of features not relevant to the analysis or with a very high variation to its value.

    - EDA : Plotted various graphs.

    - Data Type Conversion: After imputation, certain variables were cast to integer data types to reflect their nature.

## Machine Learning Models

Several machine learning models were trained and evaluated:

    Random Forest, XGBoost, Logistic Regressions, K-Nearest Neighbors (KNN),Support Vector Machine (SVM)

    Each model underwent hyperparameter tuning and cross-validation to optimize performance and prevent overfitting

## Model Evaluation

    Cross-Validation Scores, F1 and Recall values were calculated. Calculated and plotted the SHAP values

## Conclusions

The pipeline provided a thorough approach to handling missing values and training machine learning models on healthcare data. Random Forest emerged as the top-performing model, demonstrating robustness and reliability. The use of SHAP values offered insights into the models' decision-making processes and identified key features impacting predictions which were the TSH, FTI and Age.

### Packages:

- 'python': "3.11.4",
- 'numpy': "1.24.4",
- 'matplotlib': "3.7.2",
- 'sklearn': "1.3.0",
- 'pandas': "2.0.3",
- xgboost': "1.7.6",
- 'shap': "0.42.1",
- 'seaborn': "0.12.2"
