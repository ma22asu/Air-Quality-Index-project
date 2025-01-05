Air Quality Prediction Using Neural Networks and Ensemble Methods

Overview

This project predicts air quality using machine learning models applied to a dataset from an air monitoring station in Italy. It focuses on two tasks:

Regression: Predict pollutant concentrations.
Classification: Categorize air quality as "Good" or "Bad."
The project uses Google Colab for development and execution.

Features
Data Preprocessing: Handling missing values, outliers, and feature scaling.
EDA: Visualizing pollutant trends, distributions, and correlations.
Models:
Regression: Multi-Layer Perceptron (MLP) Regressor, Random Forest Regressor.
Classification: Random Forest Classifier, Logistic Regression.
Evaluation Metrics: MSE, RMSE, R² (regression); Accuracy, Precision, Recall, F1-Score (classification).
Visualizations: ROC Curve, Precision-Recall Curve, Learning Curve, Temporal Trends.
Technologies
Google Colab: Execution environment.
Python Libraries: pandas, numpy, matplotlib, seaborn, scikit-learn.
Dataset
Source: UCI Machine Learning Repository.
Key Features:
Pollutants: CO(GT), NOx(GT), C6H6(GT).
Sensors: PT08.S1(CO) to PT08.S5(O3).
Meteorology: T (Temperature), RH (Humidity), AH (Absolute Humidity).


Preprocess data.
Train regression and classification models.
Visualize results (e.g., ROC Curve, learning trends).
Results
Best Regression Model: Random Forest Regressor (R²: 0.91).
Best Classification Model: Tuned Random Forest Classifier (Accuracy: 93%).
Future Work
Real-time air quality monitoring.
Explore advanced models (e.g., Gradient Boosting, LSTM).
Generalize models using diverse datasets.
Contributing
Contributions are welcome! Open issues or submit pull requests to improve the project.

Acknowledgments
UCI Repository: Dataset provider.
Google Colab: Computational resources.
Scikit-learn: Machine learning tools.
