Data-Driven Insights and Predictions for the Pharmaceutical Industry

Project Overview:

This project analyzes the Indian pharmaceutical market to identify trends and predict the likelihood of medicine discontinuation. Leveraging a dataset of over 250,000 records, the project combines machine learning, feature engineering, and interactive visualizations to empower stakeholders with actionable insights.

Key Features

Predictive Modeling: Built and optimized machine learning models (Random Forest with class weights) to predict medicine discontinuation with an ROC-AUC score of 0.694.
Feature Engineering: Extracted and processed key attributes, including price normalization and categorical encoding, to enhance model performance.
Interactive Visualizations: Created dynamic Tableau dashboards to visualize price distributions, manufacturer trends, and high-risk products.

Technologies Used

Python: Data preprocessing, feature engineering, and model development using libraries like Pandas, Scikit-learn, and NumPy.
Machine Learning: Random Forest Classifier with class weighting to address class imbalance.
Tableau: For creating interactive dashboards showcasing trends and predictions.
Google Colab: For model training and analysis.
Google Drive: For saving and sharing output files.

Project Files

Dataset: Contains information on medicine names, prices, manufacturers, and compositions.
predictions_corrected_with_weights.csv: Final output file with predicted discontinuation status and probabilities.
Tableau Dashboards: Visualizations showcasing actionable insights for stakeholders.

How to Use

Run the Code:

Use the provided Python scripts to preprocess data, train the model, and generate predictions.
Ensure you have all required dependencies installed, including scikit-learn.
Explore Results:

Open predictions_corrected_with_weights.csv to review predicted probabilities and classes.
Import the file into Tableau for interactive visualizations.
Extend the Project:

Use the feature importance analysis to derive new insights.
Experiment with additional ML models like XGBoost or LightGBM for improved accuracy.
