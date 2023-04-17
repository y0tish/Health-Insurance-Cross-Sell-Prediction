# Health-Insurance-Cross-Sell-Prediction
The objective of this project was to help an insurance company predict whether their policyholders from the past year would be interested in vehicle insurance provided by the company. To achieve this, the project started with data cleaning and data wrangling, followed by exploratory data analysis (EDA) which included univariate, bivariate, and multivariate analysis to gain insights into the data.

After the EDA, feature engineering was performed based on the findings from the analysis. Hypothesis testing was also conducted using techniques such as Ch2, ANOVA, and T-test to identify the best features for prediction. Outliers were removed using the IQR method, and the problem of an imbalanced dataset was addressed using the SMOTE technique.

Several classification machine learning models were then trained on the preprocessed data, including Logistic Regression, Gaussian Naive Bayes, Decision Tree, Random Forest, Xtra Tree, Adaboost, and XGBoost. To evaluate the models, metrics such as precision, recall, and ROC AUC score were used.

Based on the evaluation metrics, the Adaboost model was found to have the best performance with a highest ROC AUC score of 0.7934. This means that the Adaboost model is able to accurately predict whether a customer would be interested in vehicle insurance or not, based on the information provided about demographics, vehicles, and policy.
