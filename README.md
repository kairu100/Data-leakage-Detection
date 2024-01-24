Data Leakage Detection Project
Overview
This project focuses on detecting data leakage in credit card data. It includes functionalities for data preprocessing, machine learning model training, hyperparameter tuning, outlier detection, and the identification of potential leaky predictors in time-dependent data.

Getting Started
To run this project locally, follow these steps:

Clone the repository:

bash
Copy code
git clone https://github.com/kairu100/Data-leakage-Detection.git
cd Data-leakage-Detection
Install the required dependencies:

bash
Copy code
pip install -r requirements.txt

Features
Data Collection and Preprocessing: Handle credit card data, interpret boolean values, and preprocess the dataset for analysis.

Machine Learning Model: Utilize a RandomForestClassifier for credit card prediction tasks.

Outlier Detection: Identify anomalies in the credit card dataset using the Isolation Forest algorithm.

Model Evaluation: Assess the performance of the RandomForestClassifier on a separate test set and evaluate using cross-validation metrics.

Identifying Leaky Predictors: Detect potential leaky predictors in time-dependent data.

Exploratory Data Analysis (EDA): Visualize relationships and correlations in time-dependent data using pairplots and correlation heatmaps.

Loading Pre-trained Model: Load a pre-trained model for future predictions.

Hyperparameter Tuning: Optimize the RandomForestClassifier model's performance by tuning hyperparameters.

Contributing
Contributions are welcome! Feel free to open issues or pull requests.
