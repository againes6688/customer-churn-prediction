# Customer Churn Prediction
This repository contains a machine learning model to predict customer churn. The project leverages a customer dataset and a trained model to predict whether a customer will churn (leave the service). The model is trained using the Logistic Regression, Random Forest, and XGBoost algorithms.

Project Overview
The goal of this project is to predict customer churn using the following features:

Tenure: Duration of the customer's subscription.

Usage Frequency: Frequency of service usage.

Support Calls: Number of support calls made by the customer.

Payment Delay: Delay in payment for the service.

Models Used:
Logistic Regression

Random Forest

XGBoost

Model Evaluation Metrics:
AUC-ROC

Precision, Recall, F1-Score

Brier Score

Files in the Repository
churn_model.ipynb: The trained machine learning model used for predicting customer churn.

customer_churn_dataset_testing_master.csv: The CSV file containing customer data used for training the model.

README.md: Project documentation explaining the steps and files in the repository.

Installation
Step 1: Clone the Repository
Clone this repository to your local machine:  

git clone https://github.com/againes6688/customer-churn-prediction.git
cd customer-churn-prediction

Step 2: Install Dependencies
Ensure you have Python 3.6+ installed. Then, install the required dependencies using pip:

pip install -r requirements.txt

Step 3: Load and Use the Model
Once the dependencies are installed, you can load and use the churn model (churn_model.ipynb) to predict whether a customer will churn.
