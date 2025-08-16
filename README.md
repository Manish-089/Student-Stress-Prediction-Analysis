Stress Level Analysis and Prediction
Project Description
This project aims to analyze factors contributing to stress levels based on a survey dataset and build machine learning models to predict stress levels. The analysis includes data overview, quality assessment, univariate and bivariate analysis, correlation analysis, outlier detection, feature importance, dimensionality reduction (PCA), and statistical tests. Several classification models are trained and evaluated to determine the best-performing model for stress level prediction.

Data Source
The dataset used in this project is the "Stress Level Dataset.csv".

Analysis Steps
Data Loading and Overview: Load the dataset and get a general understanding of its structure and content.
Data Quality Assessment: Check for missing values, duplicates, and data types.
Univariate Analysis: Explore the distribution of individual features.
Target Variable Analysis: Analyze the distribution of the 'stress_level' variable.
Correlation Analysis: Investigate the relationships between features and the target variable.
Multicollinearity Detection: Identify highly correlated feature pairs.
Bivariate Analysis: Visualize the relationship between top features and stress level using box plots.
Outlier Detection: Identify outliers in the dataset using the IQR method.
Feature Importance Analysis: Determine the importance of features using Mutual Information scores.
Dimensionality Reduction (PCA): Explore the possibility of reducing the number of features while retaining variance.
Statistical Tests: Perform normality tests and ANOVA tests to understand feature distributions and group differences.
ML Preprocessing Recommendations: Provide suggestions for preparing the data for machine learning models.
Model Comparison
Several classification models were trained and evaluated based on their accuracy. The results are as follows:

Model	Accuracy
                Model  Accuracy
0  Logistic Regression  0.876364
5             LightGBM  0.876364
1        Random Forest  0.872727
6                  SVM  0.869091
7                  SVM  0.869091
2    Gradient Boosting  0.865455
3             AdaBoost  0.861818
4              XGBoost  0.847273

Future Work
Perform hyperparameter tuning on the best-performing models.
Explore other classification algorithms.
Implement advanced feature engineering techniques.
Investigate the impact of outlier treatment and multicollinearity handling on model performance.
Deploy the best model for real-world stress level prediction.
